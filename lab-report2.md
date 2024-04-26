# Lab Report 2
## Part 1

```
import java.io.IOException;
import java.net.URI;

class ChatHandler implements URLHandler {
    // The one bit of state on the server: a number that will be manipulated by
    // various requests.

    String history = "";

    public String handleRequest(URI url) {
        if (url.getPath().equals("/")) {
            return String.format(history);
        }
        else {
            if (url.getPath().equals("/add-message")) {
                String[] parameters = url.getQuery().split("&");
                System.out.println(parameters[0] + " : " + parameters[1]);

                String[] message = parameters[0].split("=");
                String[] user = parameters[1].split("=");
                
                if ((message[0].equals("s")) && (user[0].equals("user"))) {
                    
                    history += user[1] + ": " + message[1] + "\n";

                    return String.format(history);
                
                }
            }
        }
        return "404 Not Found!";
    }
}


class ChatServer {
    public static void main(String[] args) throws IOException {
        if(args.length == 0){
            System.out.println("Missing port number! Try any number between 1024 to 49151");
            return;
        }

        int port = Integer.parseInt(args[0]);

        Server.start(port, new ChatHandler());
    }
}
```

![Image](chatserver1.png)
![Image](chatserver2.png)
* Ex
* Ex

## Part 2
![Image](ls_privatekey.png)
![Image](ls_publickey.png)
![Image](login_ssh.png)
## Part 3
Example
