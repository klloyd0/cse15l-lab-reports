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
*Much like above, the method `urlgetpath.equals(/add-message)` is called, which from there prompts the methods `url.getQuery().split("=")`, `parameters[0].split("=")`, `parameters[1].split("=")` and finally, provided there is a legitimate message and user string within the parameters via `message[0].equals("s")` and `user[0].equals("user")`, the method `String.format(history)` is called to print the actual message.
* Also respectively, the relevant arguments are the URL path `/add-message`, the URL query symbol `=`, and the URL query

---
![Image](chatserver2.png)
* Much like above, the method `urlgetpath.equals(/add-message)` is called, which from there prompts the methods `url.getQuery().split("=")`, `parameters[0].split("=")`, `parameters[1].split("=")` and finally, provided there is a legitimate message and user string within the parameters via `message[0].equals("s")` and `user[0].equals("user")`, the method `String.format(history)` is called to print the actual message.
* Also respectively, the relevant arguments are the URL path `/add-message`, the URL query symbol `=`, and the URL query

## Part 2
![Image](ls_privatekey.png)
![Image](ls_publickey.png)
![Image](login_ssh.png)
## Part 3
Example
