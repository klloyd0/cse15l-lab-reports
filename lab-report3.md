# Lab Report 3
## Part 2


```
$ find -name biomed
./biomed
```

```
$ find -name plos
./plos
```
* The `-name` option for the `find` command basically searches and confirms if there is a directory or file with the exact name, almost like a regular search query. If we wanted to know if there really was a directory named `biomed` for instance, we could look for that and confirm it.
* Source: https://www.ibm.com/docs/en/aix/7.2?topic=f-find-command

```
$ find government -print
government
government/About_LSC
government/About_LSC/Comments_on_semiannual.txt
government/About_LSC/commission_report.txt
government/About_LSC/conference_highlights.txt
government/About_LSC/CONFIG_STANDARDS.txt
government/About_LSC/diversity_priorities.txt
government/About_LSC/LegalServCorp_v_VelazquezDissent.txt
government/About_LSC/LegalServCorp_v_VelazquezOpinion.txt
government/About_LSC/LegalServCorp_v_VelazquezSyllabus.txt
government/About_LSC/ODonnell_et_al_v_LSCdecision.txt
government/About_LSC/ONTARIO_LEGAL_AID_SERIES.txt
government/About_LSC/Progress_report.txt
government/About_LSC/Protocol_Regarding_Access.txt
government/About_LSC/reporting_system.txt
government/About_LSC/Special_report_to_congress.txt
government/About_LSC/State_Planning_Report.txt
government/About_LSC/State_Planning_Special_Report.txt
government/About_LSC/Strategic_report.txt
government/Alcohol_Problems
government/Alcohol_Problems/DraftRecom-PDF.txt
government/Alcohol_Problems/Session2-PDF.txt
government/Alcohol_Problems/Session3-PDF.txt
government/Alcohol_Problems/Session4-PDF.txt
government/Env_Prot_Agen
government/Env_Prot_Agen/1-3_meth_901.txt
government/Env_Prot_Agen/atx1-6.txt
government/Env_Prot_Agen/bill.txt
government/Env_Prot_Agen/ctf1-6.txt
government/Env_Prot_Agen/ctf7-10.txt
government/Env_Prot_Agen/ctm4-10.txt
government/Env_Prot_Agen/final.txt
government/Env_Prot_Agen/jeffordslieberm.txt
government/Env_Prot_Agen/multi102902.txt
government/Env_Prot_Agen/nov1.txt
government/Env_Prot_Agen/ro_clear_skies_book.txt
government/Env_Prot_Agen/section-by-section_summary.txt
government/Env_Prot_Agen/tech_adden.txt
government/Env_Prot_Agen/tech_sectiong.txt
government/Gen_Account_Office
government/Gen_Account_Office/ai00134.txt
government/Gen_Account_Office/ai2132.txt
government/Gen_Account_Office/ai9868.txt
government/Gen_Account_Office/d01121g.txt
government/Gen_Account_Office/d01145g.txt
government/Gen_Account_Office/d01186g.txt
government/Gen_Account_Office/d01376g.txt
government/Gen_Account_Office/d01591sp.txt
government/Gen_Account_Office/d0269g.txt
government/Gen_Account_Office/d02701.txt
government/Gen_Account_Office/d03232sp.txt
government/Gen_Account_Office/d03273g.txt
government/Gen_Account_Office/d03419sp.txt
government/Gen_Account_Office/ffm.txt
government/Gen_Account_Office/gg96118.txt
government/Gen_Account_Office/GovernmentAuditingStandards_yb2002ed.txt
government/Gen_Account_Office/im814.txt
government/Gen_Account_Office/InternalControl_ai00021p.txt
government/Gen_Account_Office/July11-2001_gg00172r.txt
government/Gen_Account_Office/June30-2000_gg00135r.txt
government/Gen_Account_Office/Letter_Walkeraug17let.txt
government/Gen_Account_Office/Letter_WalkerJan30-2001.txt
government/Gen_Account_Office/May1998_ai98068.txt
government/Gen_Account_Office/Oct15-1999_gg00026t.txt
government/Gen_Account_Office/Oct15-2001_d0224.txt
government/Gen_Account_Office/og96009.txt
government/Gen_Account_Office/og96011.txt
government/Gen_Account_Office/og96012.txt
government/Gen_Account_Office/og96014.txt
government/Gen_Account_Office/og96015.txt
government/Gen_Account_Office/og96020.txt
government/Gen_Account_Office/og96021.txt
government/Gen_Account_Office/og96022.txt
government/Gen_Account_Office/og96023.txt
government/Gen_Account_Office/og96026.txt
government/Gen_Account_Office/og96027.txt
government/Gen_Account_Office/og96028.txt
government/Gen_Account_Office/og96031.txt
government/Gen_Account_Office/og96032.txt
government/Gen_Account_Office/og96033.txt
government/Gen_Account_Office/og96034.txt
government/Gen_Account_Office/og96036.txt
government/Gen_Account_Office/og96037.txt
government/Gen_Account_Office/og96038.txt
government/Gen_Account_Office/og96040.txt
government/Gen_Account_Office/og96041.txt
government/Gen_Account_Office/og96042.txt
government/Gen_Account_Office/og96043.txt
government/Gen_Account_Office/og96045.txt
government/Gen_Account_Office/og96047.txt
government/Gen_Account_Office/og97001.txt
government/Gen_Account_Office/og97002.txt
government/Gen_Account_Office/og97003.txt
government/Gen_Account_Office/og97011.txt
government/Gen_Account_Office/og97019.txt
government/Gen_Account_Office/og97020.txt
government/Gen_Account_Office/og97023.txt
government/Gen_Account_Office/og97028.txt
government/Gen_Account_Office/og97032.txt
government/Gen_Account_Office/og97038.txt
government/Gen_Account_Office/og97039.txt
government/Gen_Account_Office/og97041.txt
government/Gen_Account_Office/og97043.txt
government/Gen_Account_Office/og97045.txt
government/Gen_Account_Office/og97046.txt
government/Gen_Account_Office/og97050.txt
government/Gen_Account_Office/og97051.txt
government/Gen_Account_Office/og97052.txt
government/Gen_Account_Office/og98018.txt
government/Gen_Account_Office/og98019.txt
government/Gen_Account_Office/og98022.txt
government/Gen_Account_Office/og98024.txt
government/Gen_Account_Office/og98026.txt
government/Gen_Account_Office/og98029.txt
government/Gen_Account_Office/og98030.txt
government/Gen_Account_Office/og98032.txt
government/Gen_Account_Office/og98040.txt
government/Gen_Account_Office/og98041.txt
government/Gen_Account_Office/og98044.txt
government/Gen_Account_Office/og98045.txt
government/Gen_Account_Office/og98046.txt
government/Gen_Account_Office/og99036.txt
government/Gen_Account_Office/Paper_Walker11-2002_acpro122.txt
government/Gen_Account_Office/pe1019.txt
government/Gen_Account_Office/Sept14-2002_d011070.txt
government/Gen_Account_Office/Sept27-2002_d02966.txt
government/Gen_Account_Office/Statements_Feb28-1997_volume.txt
government/Gen_Account_Office/Testimony_cg00010t.txt
government/Gen_Account_Office/Testimony_d01609t.txt
government/Gen_Account_Office/Testimony_Jul15-2002_d02940t.txt
government/Gen_Account_Office/Testimony_Jul17-2002_d02957t.txt
government/Media
government/Media/5_Legal_Groups.txt
government/Media/Abuse_penalties.txt
government/Media/Advocate_for_Poor.txt
government/Media/agency_expands.txt
government/Media/Aid_Gets_7_Million.txt
government/Media/All_May_Have_Justice.txt
government/Media/Annual_Fee.txt
government/Media/Anthem_Payout.txt
government/Media/AP_LawSchoolDebts.txt
government/Media/Assuring_Underprivileged.txt
government/Media/Attorney_gives_his_time.txt
government/Media/Avoids_Budget_Cut.txt
government/Media/A_helping_hand.txt
government/Media/A_Perk_of_Age.txt
government/Media/balance_scales_of_justice.txt
government/Media/Barnes_new_job.txt
government/Media/Barnes_pro_bono.txt
government/Media/Barnes_Volunteers.txt
government/Media/Barr_sharpening_ax.txt
government/Media/BergenCountyRecord.txt
government/Media/Bias_on_the_Job.txt
government/Media/Boone_legal_service.txt
government/Media/Bridging_legal_aid_gap.txt
government/Media/BusinessWire.txt
government/Media/BusinessWire2.txt
government/Media/Butler_Co_attorneys.txt
government/Media/Campaign_Pays.txt
government/Media/City_Council_Budget.txt
government/Media/Civil_Matters.txt
government/Media/CommercialAppealMemphis2.txt
government/Media/Commercial_Appeal.txt
government/Media/Coup_Reshapes_Legal_Aid.txt
government/Media/Court_Keeps_Judge_From.txt
government/Media/Crains_New_York_Business.txt
government/Media/defend_yourself.txt
government/Media/Disaster_center.txt
government/Media/Do-it-yourself_divorce.txt
government/Media/Domestic_violence_aid.txt
government/Media/Domestic_Violence_Ruling.txt
government/Media/Donald_Hilliker.txt
government/Media/Entities_Merge.txt
government/Media/Eviction_law.txt
government/Media/families_saved.txt
government/Media/Farm_workers.txt
government/Media/Federal_agency.txt
government/Media/Few_who_need.txt
government/Media/fight_domestic_abuse.txt
government/Media/Fire_Victims_Sue.txt
government/Media/Firm_to_the_Poor_Needs_Help.txt
government/Media/FortWorthStarTelegram.txt
government/Media/Free_Legal_Assistance.txt
government/Media/Free_legal_service.txt
government/Media/Funding_cuts_force.txt
government/Media/Funding_May_Limit.txt
government/Media/Funds_Shortage.txt
government/Media/FY_04_Budget_Outlook.txt
government/Media/Ginny_Kilgore.txt
government/Media/Good_guys_reward.txt
government/Media/grants_fail_to_come.txt
government/Media/Greedy_Generous.txt
government/Media/GreensburgDailyNews.txt
government/Media/Hard_to_Get.txt
government/Media/Helping_Hands.txt
government/Media/Helping_Out.txt
government/Media/help_rent-to-own_tenants.txt
government/Media/Higher_court.txt
government/Media/Higher_Registration_Fees.txt
government/Media/highlight_Senior_Day.txt
government/Media/IOLTA_INTEREST_RATE.txt
government/Media/It_Pays_to_Know.txt
government/Media/Justice_for_all.txt
government/Media/Justice_requests.txt
government/Media/Kiosks_for_court_forms.txt
government/Media/Law-school_grads.txt
government/Media/Lawyer_Web_Survey.txt
government/Media/Law_Award_from_College.txt
government/Media/Law_Schools.txt
government/Media/Legal-aid_chief.txt
government/Media/Legal_Aid_attorney.txt
government/Media/Legal_Aid_campaign.txt
government/Media/Legal_Aid_in_Clay_County.txt
government/Media/Legal_Aid_looks_to_legislators.txt
government/Media/Legal_Aid_Society.txt
government/Media/Legal_hotline.txt
government/Media/Legal_services_for_poor.txt
government/Media/Legal_system_fails_poor.txt
government/Media/less_legal_aid.txt
government/Media/Library_Lawyers.txt
government/Media/Lindsays_legacy.txt
government/Media/Local_Attorneys.txt
government/Media/Lockyer_Warns.txt
government/Media/Low-income_children.txt
government/Media/Major_Changes.txt
government/Media/Making_a_case.txt
government/Media/man_on_national_team.txt
government/Media/Marylands_Legal_Aid.txt
government/Media/New_funding_sources.txt
government/Media/New_Online_Resources.txt
government/Media/NJ_Legal_Services.txt
government/Media/Nonprofit_Buys.txt
government/Media/not_accessible_to_disabled.txt
government/Media/Oregon_Poor.txt
government/Media/Owning_a_Piece.txt
government/Media/Paralegal_Honored.txt
government/Media/Philly_Lawyers.txt
government/Media/Politician_Practices.txt
government/Media/Poor_Lacking_Legal_Aid.txt
government/Media/Poverty_Lawyers.txt
government/Media/predatory_loans.txt
government/Media/Pro-bono_road_show.txt
government/Media/Program_Lodges.txt
government/Media/Providing_Legal_Aid.txt
government/Media/pro_bono_efforts.txt
government/Media/Pro_Bono_Services.txt
government/Media/Raising_the_Bar.txt
government/Media/Rental_rules.txt
government/Media/residents_sue_city.txt
government/Media/Retirement_Has_Its_Appeal.txt
government/Media/RoanokeTimes.txt
government/Media/Rumble_in_the_Bronx.txt
government/Media/Self-Help_Website.txt
government/Media/Service_Agency.txt
government/Media/State_funding.txt
government/Media/Supporting_Legal_Center.txt
government/Media/Survey.txt
government/Media/Targeting_Domestic_Violence.txt
government/Media/Terrorist_Attack.txt
government/Media/Texas_Lawyer.txt
government/Media/Texas_Supreme_Court.txt
government/Media/The_Bend_Bulletin.txt
government/Media/The_Columbian.txt
government/Media/The_State_of_Pro_Bono.txt
government/Media/Too_Crucial_to_Take_Cut.txt
government/Media/Towson_Attorney.txt
government/Media/Understanding.txt
government/Media/Unusual_Woodburn.txt
government/Media/Using_Tech_Tools.txt
government/Media/Valley_Needing_Legal_Services.txt
government/Media/Volunteers_Step_Up.txt
government/Media/water_fees.txt
government/Media/Weak_economy.txt
government/Media/Wilmington_lawyer.txt
government/Media/Wingates_winds.txt
government/Media/Workers_aid_center.txt
government/Media/Working_for_Free.txt
government/Post_Rate_Comm
government/Post_Rate_Comm/Cohenetal_comparison.txt
government/Post_Rate_Comm/Cohenetal_Cost_Function.txt
government/Post_Rate_Comm/Cohenetal_CreamSkimming.txt
government/Post_Rate_Comm/Cohenetal_DeliveryCost.txt
government/Post_Rate_Comm/Cohenetal_RuralDelivery.txt
government/Post_Rate_Comm/Cohenetal_Scale.txt
government/Post_Rate_Comm/Gleiman_EMASpeech.txt
government/Post_Rate_Comm/Gleiman_gca2000.txt
government/Post_Rate_Comm/Mitchell_6-17-Mit.txt
government/Post_Rate_Comm/Mitchell_RMVancouver.txt
government/Post_Rate_Comm/Mitchell_spyros-first-class.txt
government/Post_Rate_Comm/Redacted_Study.txt
government/Post_Rate_Comm/ReportToCongress2002WEB.txt
government/Post_Rate_Comm/WolakSpeech_usps.txt
```
```
$ find 911report -print
911report
911report/chapter-1.txt
911report/chapter-10.txt
911report/chapter-11.txt
911report/chapter-12.txt
911report/chapter-13.1.txt
911report/chapter-13.2.txt
911report/chapter-13.3.txt
911report/chapter-13.4.txt
911report/chapter-13.5.txt
911report/chapter-2.txt
911report/chapter-3.txt
911report/chapter-5.txt
911report/chapter-6.txt
911report/chapter-7.txt
911report/chapter-8.txt
911report/chapter-9.txt
911report/preface.txt
```
* The `-print` option after the `find` command basically prints all paths beginning with the current path name. This could be really useful as a means of viewing what's inside each directory within `technical` without using the `cd` and `ls` commands to view each child directory one by one.

```
$ find -type d
.
./911report
./biomed
./government
./government/About_LSC
./government/Alcohol_Problems
./government/Env_Prot_Agen
./government/Gen_Account_Office
./government/Media
./government/Post_Rate_Comm
./plos
```

```
$ find -type f
./biomed/1471-2334-1-9.txt
./biomed/1471-2334-2-1.txt
./biomed/1471-2334-2-24.txt
./biomed/1471-2334-2-26.txt
./biomed/1471-2334-2-27.txt
./biomed/1471-2334-2-29.txt
./biomed/1471-2334-2-5.txt
./biomed/1471-2334-2-6.txt
./biomed/1471-2334-2-7.txt
./biomed/1471-2334-3-10.txt
./biomed/1471-2334-3-11.txt
./biomed/1471-2334-3-12.txt
./biomed/1471-2334-3-13.txt
./biomed/1471-2334-3-15.txt
./biomed/1471-2334-3-9.txt
./biomed/1471-2350-2-11.txt
./biomed/1471-2350-2-12.txt
./biomed/1471-2350-2-2.txt
./biomed/1471-2350-2-8.txt
./biomed/1471-2350-3-1.txt
./biomed/1471-2350-3-12.txt
./biomed/1471-2350-3-7.txt
./biomed/1471-2350-3-9.txt
./biomed/1471-2350-4-2.txt
./biomed/1471-2350-4-3.txt
./biomed/1471-2350-4-4.txt
./biomed/1471-2350-4-6.txt
./biomed/1471-2369-3-1.txt
./biomed/1471-2369-3-10.txt
./biomed/1471-2369-3-6.txt
./biomed/1471-2369-3-9.txt
./biomed/1471-2369-4-1.txt
./biomed/1471-2369-4-5.txt
./biomed/1471-2377-1-2.txt
./biomed/1471-2377-2-4.txt
./biomed/1471-2377-2-6.txt
./biomed/1471-2377-3-4.txt
./biomed/1471-2407-1-13.txt
./biomed/1471-2407-1-15.txt
./biomed/1471-2407-1-19.txt
./biomed/1471-2407-1-6.txt
./biomed/1471-2407-2-11.txt
./biomed/1471-2407-2-12.txt
./biomed/1471-2407-2-15.txt
./biomed/1471-2407-2-16.txt
./biomed/1471-2407-2-17.txt
./biomed/1471-2407-2-18.txt
./biomed/1471-2407-2-19.txt
./biomed/1471-2407-2-22.txt
./biomed/1471-2407-2-23.txt
./biomed/1471-2407-2-3.txt
./biomed/1471-2407-2-31.txt
./biomed/1471-2407-2-33.txt
./biomed/1471-2407-2-8.txt
./biomed/1471-2407-2-9.txt
./biomed/1471-2407-3-14.txt
./biomed/1471-2407-3-15.txt
./biomed/1471-2407-3-16.txt
./biomed/1471-2407-3-18.txt
./biomed/1471-2407-3-3.txt
./biomed/1471-2407-3-4.txt
./biomed/1471-2407-3-5.txt
./biomed/1471-2415-3-1.txt
./biomed/1471-2415-3-3.txt
./biomed/1471-2415-3-4.txt
./biomed/1471-2415-3-5.txt
./biomed/1471-2431-2-1.txt
./biomed/1471-2431-2-11.txt
./biomed/1471-2431-2-12.txt
./biomed/1471-2431-2-4.txt
./biomed/1471-2431-3-3.txt
./biomed/1471-2431-3-4.txt
./biomed/1471-2431-3-5.txt
./biomed/1471-2431-3-6.txt
./biomed/1471-244X-2-9.txt
./biomed/1471-244X-3-5.txt
./biomed/1471-2458-1-9.txt
./biomed/1471-2458-2-11.txt
./biomed/1471-2458-2-16.txt
./biomed/1471-2458-2-18.txt
./biomed/1471-2458-2-21.txt
./biomed/1471-2458-2-25.txt
./biomed/1471-2458-2-3.txt
./biomed/1471-2458-2-6.txt
./biomed/1471-2458-3-11.txt
./biomed/1471-2458-3-2.txt
./biomed/1471-2458-3-20.txt
./biomed/1471-2458-3-5.txt
./biomed/1471-2458-3-9.txt
./biomed/1471-2466-1-1.txt
./biomed/1471-2466-2-3.txt
./biomed/1471-2466-2-4.txt
./biomed/1471-2466-3-1.txt
./biomed/1471-2474-2-1.txt
./biomed/1471-2474-2-2.txt
./biomed/1471-2474-2-3.txt
./biomed/1471-2474-3-23.txt
./biomed/1471-2474-3-3.txt
./biomed/1471-2474-4-4.txt
./biomed/1471-2474-4-8.txt
./biomed/1471-2490-3-2.txt
./biomed/1471-5945-1-3.txt
./biomed/1471-5945-2-13.txt
./biomed/1471-5945-3-3.txt
./biomed/1472-6750-1-11.txt
./biomed/1472-6750-1-12.txt
./biomed/1472-6750-1-13.txt
./biomed/1472-6750-1-6.txt
./biomed/1472-6750-1-8.txt
./biomed/1472-6750-2-10.txt
./biomed/1472-6750-2-13.txt
./biomed/1472-6750-2-14.txt
./biomed/1472-6750-2-2.txt
./biomed/1472-6750-2-21.txt
./biomed/1472-6750-3-11.txt
./biomed/1472-6750-3-4.txt
./biomed/1472-6750-3-6.txt
./biomed/1472-6769-1-1.txt
./biomed/1472-6769-1-2.txt
./biomed/1472-6769-1-3.txt
./biomed/1472-6769-1-4.txt
./biomed/1472-6785-1-3.txt
./biomed/1472-6785-1-5.txt
./biomed/1472-6785-2-6.txt
./biomed/1472-6785-2-7.txt
./biomed/1472-6793-1-11.txt
./biomed/1472-6793-1-12.txt
./biomed/1472-6793-1-15.txt
./biomed/1472-6793-1-2.txt
./biomed/1472-6793-1-6.txt
./biomed/1472-6793-1-8.txt
./biomed/1472-6793-2-1.txt
./biomed/1472-6793-2-11.txt
./biomed/1472-6793-2-16.txt
./biomed/1472-6793-2-17.txt
./biomed/1472-6793-2-18.txt
./biomed/1472-6793-2-19.txt
./biomed/1472-6793-2-2.txt
./biomed/1472-6793-2-4.txt
./biomed/1472-6793-2-5.txt
./biomed/1472-6793-2-8.txt
./biomed/1472-6793-3-3.txt
./biomed/1472-6793-3-4.txt
./biomed/1472-6793-3-5.txt
./biomed/1472-6793-3-6.txt
./biomed/1472-6807-1-1.txt
./biomed/1472-6807-2-1.txt
./biomed/1472-6807-2-2.txt
./biomed/1472-6807-2-3.txt
./biomed/1472-6807-2-4.txt
./biomed/1472-6807-2-5.txt
./biomed/1472-6807-2-9.txt
./biomed/1472-6807-3-1.txt
./biomed/1472-6807-3-2.txt
./biomed/1472-6815-2-3.txt
./biomed/1472-6823-2-2.txt
./biomed/1472-6823-3-1.txt
./biomed/1472-6831-2-2.txt
./biomed/1472-6831-3-1.txt
./biomed/1472-684X-1-5.txt
./biomed/1472-684X-2-1.txt
./biomed/1472-684X-2-2.txt
./biomed/1472-6874-2-1.txt
./biomed/1472-6874-2-13.txt
./biomed/1472-6874-2-8.txt
./biomed/1472-6874-3-2.txt
./biomed/1472-6882-1-10.txt
./biomed/1472-6882-1-11.txt
./biomed/1472-6882-1-12.txt
./biomed/1472-6882-1-7.txt
./biomed/1472-6882-2-10.txt
./biomed/1472-6882-2-5.txt
./biomed/1472-6882-3-1.txt
./biomed/1472-6882-3-3.txt
./biomed/1472-6890-1-4.txt
./biomed/1472-6890-2-5.txt
./biomed/1472-6890-3-2.txt
./biomed/1472-6904-1-2.txt
./biomed/1472-6904-2-4.txt
./biomed/1472-6904-2-5.txt
./biomed/1472-6904-2-7.txt
./biomed/1472-6904-3-1.txt
./biomed/1472-6920-1-3.txt
./biomed/1472-6920-2-1.txt
./biomed/1472-6920-2-3.txt
./biomed/1472-6947-1-2.txt
./biomed/1472-6947-1-5.txt
./biomed/1472-6947-1-6.txt
./biomed/1472-6947-2-4.txt
./biomed/1472-6947-2-7.txt
./biomed/1472-6947-3-5.txt
./biomed/1472-6947-3-8.txt
./biomed/1472-6955-2-1.txt
./biomed/1472-6963-1-11.txt
./biomed/1472-6963-1-8.txt
./biomed/1472-6963-2-10.txt
./biomed/1472-6963-3-1.txt
./biomed/1472-6963-3-11.txt
./biomed/1472-6963-3-12.txt
./biomed/1472-6963-3-13.txt
./biomed/1472-6963-3-14.txt
./biomed/1472-6963-3-6.txt
./biomed/1472-6963-3-7.txt
./biomed/1475-2832-1-1.txt
./biomed/1475-2867-2-10.txt
./biomed/1475-2867-2-15.txt
./biomed/1475-2867-2-7.txt
./biomed/1475-2867-3-12.txt
./biomed/1475-2867-3-2.txt
./biomed/1475-2867-3-3.txt
./biomed/1475-2867-3-4.txt
./biomed/1475-2875-1-14.txt
./biomed/1475-2875-1-5.txt
./biomed/1475-2875-2-10.txt
./biomed/1475-2875-2-14.txt
./biomed/1475-2875-2-4.txt
./biomed/1475-2883-2-11.txt
./biomed/1475-2891-1-2.txt
./biomed/1475-2891-2-1.txt
./biomed/1475-4924-1-10.txt
./biomed/1475-4924-1-5.txt
./biomed/1475-925X-2-1.txt
./biomed/1475-925X-2-10.txt
./biomed/1475-925X-2-11.txt
./biomed/1475-925X-2-12.txt
./biomed/1475-925X-2-3.txt
./biomed/1475-925X-2-6.txt
./biomed/1475-9268-1-1.txt
./biomed/1475-9268-1-2.txt
./biomed/1475-9276-1-3.txt
./biomed/1476-069X-1-3.txt
./biomed/1476-069X-2-2.txt
./biomed/1476-069X-2-4.txt
./biomed/1476-069X-2-7.txt
./biomed/1476-069X-2-9.txt
./biomed/1476-0711-2-3.txt
./biomed/1476-0711-2-7.txt
./biomed/1476-072X-2-3.txt
./biomed/1476-072X-2-4.txt
./biomed/1476-4598-1-3.txt
./biomed/1476-4598-1-5.txt
./biomed/1476-4598-1-6.txt
./biomed/1476-4598-1-8.txt
./biomed/1476-4598-2-1.txt
./biomed/1476-4598-2-2.txt
./biomed/1476-4598-2-20.txt
./biomed/1476-4598-2-22.txt
./biomed/1476-4598-2-24.txt
./biomed/1476-4598-2-25.txt
./biomed/1476-4598-2-28.txt
./biomed/1476-4598-2-3.txt
./biomed/1476-511X-1-2.txt
./biomed/1476-511X-2-2.txt
./biomed/1476-511X-2-3.txt
./biomed/1476-5918-1-2.txt
./biomed/1476-9433-1-2.txt
./biomed/1476-9433-1-3.txt
./biomed/1477-5956-1-1.txt
./biomed/1477-7525-1-10.txt
./biomed/1477-7525-1-12.txt
./biomed/1477-7525-1-9.txt
./biomed/1477-7819-1-10.txt
./biomed/1477-7827-1-13.txt
./biomed/1477-7827-1-17.txt
./biomed/1477-7827-1-21.txt
./biomed/1477-7827-1-23.txt
./biomed/1477-7827-1-27.txt
./biomed/1477-7827-1-31.txt
./biomed/1477-7827-1-36.txt
./biomed/1477-7827-1-43.txt
./biomed/1477-7827-1-46.txt
./biomed/1477-7827-1-48.txt
./biomed/1477-7827-1-54.txt
./biomed/1477-7827-1-6.txt
./biomed/1477-7827-1-9.txt
./biomed/1478-1336-1-2.txt
./biomed/1478-1336-1-3.txt
./biomed/1478-1336-1-4.txt
./biomed/1478-7954-1-3.txt
./biomed/ar104.txt
./biomed/ar118.txt
./biomed/ar120.txt
./biomed/ar130.txt
./biomed/ar140.txt
./biomed/ar149.txt
./biomed/ar297.txt
./biomed/ar309.txt
./biomed/ar319.txt
./biomed/ar321.txt
./biomed/ar328.txt
./biomed/ar331.txt
./biomed/ar383.txt
./biomed/ar387.txt
./biomed/ar407.txt
./biomed/ar408.txt
./biomed/ar409.txt
./biomed/ar422.txt
./biomed/ar429.txt
./biomed/ar430.txt
./biomed/ar601.txt
./biomed/ar612.txt
./biomed/ar615.txt
./biomed/ar619.txt
./biomed/ar624.txt
./biomed/ar68.txt
./biomed/ar745.txt
./biomed/ar750.txt
./biomed/ar774.txt
./biomed/ar778.txt
./biomed/ar79.txt
./biomed/ar792.txt
./biomed/ar795.txt
./biomed/ar799.txt
./biomed/ar93.txt
./biomed/bcr273.txt
./biomed/bcr284.txt
./biomed/bcr285.txt
./biomed/bcr294.txt
./biomed/bcr303.txt
./biomed/bcr317.txt
./biomed/bcr45.txt
./biomed/bcr458.txt
./biomed/bcr567.txt
./biomed/bcr568.txt
./biomed/bcr570.txt
./biomed/bcr571.txt
./biomed/bcr583.txt
./biomed/bcr588.txt
./biomed/bcr602.txt
./biomed/bcr605.txt
./biomed/bcr607.txt
./biomed/bcr618.txt
./biomed/bcr620.txt
./biomed/bcr631.txt
./biomed/bcr635.txt
./biomed/cc103.txt
./biomed/cc1044.txt
./biomed/cc105.txt
./biomed/cc1476.txt
./biomed/cc1477.txt
./biomed/cc1495.txt
./biomed/cc1497.txt
./biomed/cc1498.txt
./biomed/cc1529.txt
./biomed/cc1538.txt
./biomed/cc1547.txt
./biomed/cc1843.txt
./biomed/cc1852.txt
./biomed/cc1856.txt
./biomed/cc1882.txt
./biomed/cc2160.txt
./biomed/cc2167.txt
./biomed/cc2171.txt
./biomed/cc2172.txt
./biomed/cc2190.txt
./biomed/cc2358.txt
./biomed/cc3.txt
./biomed/cc300.txt
./biomed/cc303.txt
./biomed/cc343.txt
./biomed/cc350.txt
./biomed/cc367.txt
./biomed/cc4.txt
./biomed/cc713.txt
./biomed/cc973.txt
./biomed/cc991.txt
./biomed/cvm-2-1-038.txt
./biomed/cvm-2-4-180.txt
./biomed/cvm-2-4-187.txt
./biomed/cvm-2-6-278.txt
./biomed/cvm-2-6-286.txt
./biomed/gb-2000-1-1-research002.txt
./biomed/gb-2000-1-2-research0003.txt
./biomed/gb-2001-2-10-research0041.txt
./biomed/gb-2001-2-10-research0042.txt
./biomed/gb-2001-2-11-research0045.txt
./biomed/gb-2001-2-11-research0046.txt
./biomed/gb-2001-2-12-research0051.txt
./biomed/gb-2001-2-12-research0053.txt
./biomed/gb-2001-2-12-research0054.txt
./biomed/gb-2001-2-12-research0055.txt
./biomed/gb-2001-2-2-research0004.txt
./biomed/gb-2001-2-3-research0007.txt
./biomed/gb-2001-2-3-research0008.txt
./biomed/gb-2001-2-4-research0010.txt
./biomed/gb-2001-2-4-research0011.txt
./biomed/gb-2001-2-4-research0012.txt
./biomed/gb-2001-2-4-research0014.txt
./biomed/gb-2001-2-6-research0018.txt
./biomed/gb-2001-2-6-research0020.txt
./biomed/gb-2001-2-6-research0021.txt
./biomed/gb-2001-2-7-research0024.txt
./biomed/gb-2001-2-7-research0025.txt
./biomed/gb-2001-2-8-research0027.txt
./biomed/gb-2001-2-8-research0030.txt
./biomed/gb-2001-2-8-research0031.txt
./biomed/gb-2001-2-8-research0032.txt
./biomed/gb-2001-2-9-research0035.txt
./biomed/gb-2001-2-9-research0037.txt
./biomed/gb-2001-3-1-research0001.txt
./biomed/gb-2001-3-1-research0004.txt
./biomed/gb-2001-3-1-research0005.txt
./biomed/gb-2002-3-10-research0052.txt
./biomed/gb-2002-3-10-research0053.txt
./biomed/gb-2002-3-10-research0054.txt
./biomed/gb-2002-3-10-research0055.txt
./biomed/gb-2002-3-10-research0056.txt
./biomed/gb-2002-3-11-research0059.txt
./biomed/gb-2002-3-11-research0060.txt
./biomed/gb-2002-3-11-research0061.txt
./biomed/gb-2002-3-11-research0062.txt
./biomed/gb-2002-3-11-research0065.txt
./biomed/gb-2002-3-12-research0071.txt
./biomed/gb-2002-3-12-research0072.txt
./biomed/gb-2002-3-12-research0075.txt
./biomed/gb-2002-3-12-research0077.txt
./biomed/gb-2002-3-12-research0078.txt
./biomed/gb-2002-3-12-research0079.txt
./biomed/gb-2002-3-12-research0080.txt
./biomed/gb-2002-3-12-research0081.txt
./biomed/gb-2002-3-12-research0082.txt
./biomed/gb-2002-3-12-research0083.txt
./biomed/gb-2002-3-12-research0085.txt
./biomed/gb-2002-3-12-research0086.txt
./biomed/gb-2002-3-12-research0087.txt
./biomed/gb-2002-3-12-research0088.txt
./biomed/gb-2002-3-2-research0008.txt
./biomed/gb-2002-3-2-research0009.txt
./biomed/gb-2002-3-3-research0011.txt
./biomed/gb-2002-3-3-research0012.txt
./biomed/gb-2002-3-4-research0018.txt
./biomed/gb-2002-3-4-research0019.txt
./biomed/gb-2002-3-5-research0020.txt
./biomed/gb-2002-3-5-research0021.txt
./biomed/gb-2002-3-5-research0022.txt
./biomed/gb-2002-3-5-research0023.txt
./biomed/gb-2002-3-5-research0024.txt
./biomed/gb-2002-3-5-research0025.txt
./biomed/gb-2002-3-6-research0029.txt
./biomed/gb-2002-3-6-software0001.txt
./biomed/gb-2002-3-7-research0032.txt
./biomed/gb-2002-3-7-research0035.txt
./biomed/gb-2002-3-7-research0036.txt
./biomed/gb-2002-3-7-research0037.txt
./biomed/gb-2002-3-8-research0038.txt
./biomed/gb-2002-3-8-research0039.txt
./biomed/gb-2002-3-8-research0040.txt
./biomed/gb-2002-3-9-research0043.txt
./biomed/gb-2002-3-9-research0044.txt
./biomed/gb-2002-3-9-research0045.txt
./biomed/gb-2002-3-9-research0046.txt
./biomed/gb-2002-3-9-research0048.txt
./biomed/gb-2002-3-9-research0049.txt
./biomed/gb-2002-3-9-research0051.txt
./biomed/gb-2002-4-1-r1.txt
./biomed/gb-2002-4-1-r2.txt
./biomed/gb-2003-4-1-r5.txt
./biomed/gb-2003-4-1-r7.txt
./biomed/gb-2003-4-2-r11.txt
./biomed/gb-2003-4-2-r14.txt
./biomed/gb-2003-4-2-r16.txt
./biomed/gb-2003-4-2-r8.txt
./biomed/gb-2003-4-2-r9.txt
./biomed/gb-2003-4-3-r17.txt
./biomed/gb-2003-4-3-r18.txt
./biomed/gb-2003-4-3-r20.txt
./biomed/gb-2003-4-4-r24.txt
./biomed/gb-2003-4-4-r26.txt
./biomed/gb-2003-4-4-r28.txt
./biomed/gb-2003-4-5-r30.txt
./biomed/gb-2003-4-5-r32.txt
./biomed/gb-2003-4-5-r34.txt
./biomed/gb-2003-4-6-r37.txt
./biomed/gb-2003-4-6-r39.txt
./biomed/gb-2003-4-6-r41.txt
./biomed/gb-2003-4-7-r42.txt
./biomed/gb-2003-4-7-r43.txt
./biomed/gb-2003-4-7-r46.txt
./biomed/gb-2003-4-8-r50.txt
./biomed/gb-2003-4-8-r51.txt
./biomed/gb-2003-4-9-r57.txt
./biomed/gb-2003-4-9-r58.txt
./biomed/gb-2003-4-9-r60.txt
./biomed/rr166.txt
./biomed/rr167.txt
./biomed/rr171.txt
./biomed/rr172.txt
./biomed/rr191.txt
./biomed/rr196.txt
./biomed/rr37.txt
./biomed/rr73.txt
./biomed/rr74.txt
./government/About_LSC/Comments_on_semiannual.txt
./government/About_LSC/commission_report.txt
./government/About_LSC/conference_highlights.txt
./government/About_LSC/CONFIG_STANDARDS.txt
./government/About_LSC/diversity_priorities.txt
./government/About_LSC/LegalServCorp_v_VelazquezDissent.txt
./government/About_LSC/LegalServCorp_v_VelazquezOpinion.txt
./government/About_LSC/LegalServCorp_v_VelazquezSyllabus.txt
./government/About_LSC/ODonnell_et_al_v_LSCdecision.txt
./government/About_LSC/ONTARIO_LEGAL_AID_SERIES.txt
./government/About_LSC/Progress_report.txt
./government/About_LSC/Protocol_Regarding_Access.txt
./government/About_LSC/reporting_system.txt
./government/About_LSC/Special_report_to_congress.txt
./government/About_LSC/State_Planning_Report.txt
./government/About_LSC/State_Planning_Special_Report.txt
./government/About_LSC/Strategic_report.txt
./government/Alcohol_Problems/DraftRecom-PDF.txt
./government/Alcohol_Problems/Session2-PDF.txt
./government/Alcohol_Problems/Session3-PDF.txt
./government/Alcohol_Problems/Session4-PDF.txt
./government/Env_Prot_Agen/1-3_meth_901.txt
./government/Env_Prot_Agen/atx1-6.txt
./government/Env_Prot_Agen/bill.txt
./government/Env_Prot_Agen/ctf1-6.txt
./government/Env_Prot_Agen/ctf7-10.txt
./government/Env_Prot_Agen/ctm4-10.txt
./government/Env_Prot_Agen/final.txt
./government/Env_Prot_Agen/jeffordslieberm.txt
./government/Env_Prot_Agen/multi102902.txt
./government/Env_Prot_Agen/nov1.txt
./government/Env_Prot_Agen/ro_clear_skies_book.txt
./government/Env_Prot_Agen/section-by-section_summary.txt
./government/Env_Prot_Agen/tech_adden.txt
./government/Env_Prot_Agen/tech_sectiong.txt
./government/Gen_Account_Office/ai00134.txt
./government/Gen_Account_Office/ai2132.txt
./government/Gen_Account_Office/ai9868.txt
./government/Gen_Account_Office/d01121g.txt
./government/Gen_Account_Office/d01145g.txt
./government/Gen_Account_Office/d01186g.txt
./government/Gen_Account_Office/d01376g.txt
./government/Gen_Account_Office/d01591sp.txt
./government/Gen_Account_Office/d0269g.txt
./government/Gen_Account_Office/d02701.txt
./government/Gen_Account_Office/d03232sp.txt
./government/Gen_Account_Office/d03273g.txt
./government/Gen_Account_Office/d03419sp.txt
./government/Gen_Account_Office/ffm.txt
./government/Gen_Account_Office/gg96118.txt
./government/Gen_Account_Office/GovernmentAuditingStandards_yb2002ed.txt
./government/Gen_Account_Office/im814.txt
./government/Gen_Account_Office/InternalControl_ai00021p.txt
./government/Gen_Account_Office/July11-2001_gg00172r.txt
./government/Gen_Account_Office/June30-2000_gg00135r.txt
./government/Gen_Account_Office/Letter_Walkeraug17let.txt
./government/Gen_Account_Office/Letter_WalkerJan30-2001.txt
./government/Gen_Account_Office/May1998_ai98068.txt
./government/Gen_Account_Office/Oct15-1999_gg00026t.txt
./government/Gen_Account_Office/Oct15-2001_d0224.txt
./government/Gen_Account_Office/og96009.txt
./government/Gen_Account_Office/og96011.txt
./government/Gen_Account_Office/og96012.txt
./government/Gen_Account_Office/og96014.txt
./government/Gen_Account_Office/og96015.txt
./government/Gen_Account_Office/og96020.txt
./government/Gen_Account_Office/og96021.txt
./government/Gen_Account_Office/og96022.txt
./government/Gen_Account_Office/og96023.txt
./government/Gen_Account_Office/og96026.txt
./government/Gen_Account_Office/og96027.txt
./government/Gen_Account_Office/og96028.txt
./government/Gen_Account_Office/og96031.txt
./government/Gen_Account_Office/og96032.txt
./government/Gen_Account_Office/og96033.txt
./government/Gen_Account_Office/og96034.txt
./government/Gen_Account_Office/og96036.txt
./government/Gen_Account_Office/og96037.txt
./government/Gen_Account_Office/og96038.txt
./government/Gen_Account_Office/og96040.txt
./government/Gen_Account_Office/og96041.txt
./government/Gen_Account_Office/og96042.txt
./government/Gen_Account_Office/og96043.txt
./government/Gen_Account_Office/og96045.txt
./government/Gen_Account_Office/og96047.txt
./government/Gen_Account_Office/og97001.txt
./government/Gen_Account_Office/og97002.txt
./government/Gen_Account_Office/og97003.txt
./government/Gen_Account_Office/og97011.txt
./government/Gen_Account_Office/og97019.txt
./government/Gen_Account_Office/og97020.txt
./government/Gen_Account_Office/og97023.txt
./government/Gen_Account_Office/og97028.txt
./government/Gen_Account_Office/og97032.txt
./government/Gen_Account_Office/og97038.txt
./government/Gen_Account_Office/og97039.txt
./government/Gen_Account_Office/og97041.txt
./government/Gen_Account_Office/og97043.txt
./government/Gen_Account_Office/og97045.txt
./government/Gen_Account_Office/og97046.txt
./government/Gen_Account_Office/og97050.txt
./government/Gen_Account_Office/og97051.txt
./government/Gen_Account_Office/og97052.txt
./government/Gen_Account_Office/og98018.txt
./government/Gen_Account_Office/og98019.txt
./government/Gen_Account_Office/og98022.txt
./government/Gen_Account_Office/og98024.txt
./government/Gen_Account_Office/og98026.txt
./government/Gen_Account_Office/og98029.txt
./government/Gen_Account_Office/og98030.txt
./government/Gen_Account_Office/og98032.txt
./government/Gen_Account_Office/og98040.txt
./government/Gen_Account_Office/og98041.txt
./government/Gen_Account_Office/og98044.txt
./government/Gen_Account_Office/og98045.txt
./government/Gen_Account_Office/og98046.txt
./government/Gen_Account_Office/og99036.txt
./government/Gen_Account_Office/Paper_Walker11-2002_acpro122.txt
./government/Gen_Account_Office/pe1019.txt
./government/Gen_Account_Office/Sept14-2002_d011070.txt
./government/Gen_Account_Office/Sept27-2002_d02966.txt
./government/Gen_Account_Office/Statements_Feb28-1997_volume.txt
./government/Gen_Account_Office/Testimony_cg00010t.txt
./government/Gen_Account_Office/Testimony_d01609t.txt
./government/Gen_Account_Office/Testimony_Jul15-2002_d02940t.txt
./government/Gen_Account_Office/Testimony_Jul17-2002_d02957t.txt
./government/Media/5_Legal_Groups.txt
./government/Media/Abuse_penalties.txt
./government/Media/Advocate_for_Poor.txt
./government/Media/agency_expands.txt
./government/Media/Aid_Gets_7_Million.txt
./government/Media/All_May_Have_Justice.txt
./government/Media/Annual_Fee.txt
./government/Media/Anthem_Payout.txt
./government/Media/AP_LawSchoolDebts.txt
./government/Media/Assuring_Underprivileged.txt
./government/Media/Attorney_gives_his_time.txt
./government/Media/Avoids_Budget_Cut.txt
./government/Media/A_helping_hand.txt
./government/Media/A_Perk_of_Age.txt
./government/Media/balance_scales_of_justice.txt
./government/Media/Barnes_new_job.txt
./government/Media/Barnes_pro_bono.txt
./government/Media/Barnes_Volunteers.txt
./government/Media/Barr_sharpening_ax.txt
./government/Media/BergenCountyRecord.txt
./government/Media/Bias_on_the_Job.txt
./government/Media/Boone_legal_service.txt
./government/Media/Bridging_legal_aid_gap.txt
./government/Media/BusinessWire.txt
./government/Media/BusinessWire2.txt
./government/Media/Butler_Co_attorneys.txt
./government/Media/Campaign_Pays.txt
./government/Media/City_Council_Budget.txt
./government/Media/Civil_Matters.txt
./government/Media/CommercialAppealMemphis2.txt
./government/Media/Commercial_Appeal.txt
./government/Media/Coup_Reshapes_Legal_Aid.txt
./government/Media/Court_Keeps_Judge_From.txt
./government/Media/Crains_New_York_Business.txt
./government/Media/defend_yourself.txt
./government/Media/Disaster_center.txt
./government/Media/Do-it-yourself_divorce.txt
./government/Media/Domestic_violence_aid.txt
./government/Media/Domestic_Violence_Ruling.txt
./government/Media/Donald_Hilliker.txt
./government/Media/Entities_Merge.txt
./government/Media/Eviction_law.txt
./government/Media/families_saved.txt
./government/Media/Farm_workers.txt
./government/Media/Federal_agency.txt
./government/Media/Few_who_need.txt
./government/Media/fight_domestic_abuse.txt
./government/Media/Fire_Victims_Sue.txt
./government/Media/Firm_to_the_Poor_Needs_Help.txt
./government/Media/FortWorthStarTelegram.txt
./government/Media/Free_Legal_Assistance.txt
./government/Media/Free_legal_service.txt
./government/Media/Funding_cuts_force.txt
./government/Media/Funding_May_Limit.txt
./government/Media/Funds_Shortage.txt
./government/Media/FY_04_Budget_Outlook.txt
./government/Media/Ginny_Kilgore.txt
./government/Media/Good_guys_reward.txt
./government/Media/grants_fail_to_come.txt
./government/Media/Greedy_Generous.txt
./government/Media/GreensburgDailyNews.txt
./government/Media/Hard_to_Get.txt
./government/Media/Helping_Hands.txt
./government/Media/Helping_Out.txt
./government/Media/help_rent-to-own_tenants.txt
./government/Media/Higher_court.txt
./government/Media/Higher_Registration_Fees.txt
./government/Media/highlight_Senior_Day.txt
./government/Media/IOLTA_INTEREST_RATE.txt
./government/Media/It_Pays_to_Know.txt
./government/Media/Justice_for_all.txt
./government/Media/Justice_requests.txt
./government/Media/Kiosks_for_court_forms.txt
./government/Media/Law-school_grads.txt
./government/Media/Lawyer_Web_Survey.txt
./government/Media/Law_Award_from_College.txt
./government/Media/Law_Schools.txt
./government/Media/Legal-aid_chief.txt
./government/Media/Legal_Aid_attorney.txt
./government/Media/Legal_Aid_campaign.txt
./government/Media/Legal_Aid_in_Clay_County.txt
./government/Media/Legal_Aid_looks_to_legislators.txt
./government/Media/Legal_Aid_Society.txt
./government/Media/Legal_hotline.txt
./government/Media/Legal_services_for_poor.txt
./government/Media/Legal_system_fails_poor.txt
./government/Media/less_legal_aid.txt
./government/Media/Library_Lawyers.txt
./government/Media/Lindsays_legacy.txt
./government/Media/Local_Attorneys.txt
./government/Media/Lockyer_Warns.txt
./government/Media/Low-income_children.txt
./government/Media/Major_Changes.txt
./government/Media/Making_a_case.txt
./government/Media/man_on_national_team.txt
./government/Media/Marylands_Legal_Aid.txt
./government/Media/New_funding_sources.txt
./government/Media/New_Online_Resources.txt
./government/Media/NJ_Legal_Services.txt
./government/Media/Nonprofit_Buys.txt
./government/Media/not_accessible_to_disabled.txt
./government/Media/Oregon_Poor.txt
./government/Media/Owning_a_Piece.txt
./government/Media/Paralegal_Honored.txt
./government/Media/Philly_Lawyers.txt
./government/Media/Politician_Practices.txt
./government/Media/Poor_Lacking_Legal_Aid.txt
./government/Media/Poverty_Lawyers.txt
./government/Media/predatory_loans.txt
./government/Media/Pro-bono_road_show.txt
./government/Media/Program_Lodges.txt
./government/Media/Providing_Legal_Aid.txt
./government/Media/pro_bono_efforts.txt
./government/Media/Pro_Bono_Services.txt
./government/Media/Raising_the_Bar.txt
./government/Media/Rental_rules.txt
./government/Media/residents_sue_city.txt
./government/Media/Retirement_Has_Its_Appeal.txt
./government/Media/RoanokeTimes.txt
./government/Media/Rumble_in_the_Bronx.txt
./government/Media/Self-Help_Website.txt
./government/Media/Service_Agency.txt
./government/Media/State_funding.txt
./government/Media/Supporting_Legal_Center.txt
./government/Media/Survey.txt
./government/Media/Targeting_Domestic_Violence.txt
./government/Media/Terrorist_Attack.txt
./government/Media/Texas_Lawyer.txt
./government/Media/Texas_Supreme_Court.txt
./government/Media/The_Bend_Bulletin.txt
./government/Media/The_Columbian.txt
./government/Media/The_State_of_Pro_Bono.txt
./government/Media/Too_Crucial_to_Take_Cut.txt
./government/Media/Towson_Attorney.txt
./government/Media/Understanding.txt
./government/Media/Unusual_Woodburn.txt
./government/Media/Using_Tech_Tools.txt
./government/Media/Valley_Needing_Legal_Services.txt
./government/Media/Volunteers_Step_Up.txt
./government/Media/water_fees.txt
./government/Media/Weak_economy.txt
./government/Media/Wilmington_lawyer.txt
./government/Media/Wingates_winds.txt
./government/Media/Workers_aid_center.txt
./government/Media/Working_for_Free.txt
./government/Post_Rate_Comm/Cohenetal_comparison.txt
./government/Post_Rate_Comm/Cohenetal_Cost_Function.txt
./government/Post_Rate_Comm/Cohenetal_CreamSkimming.txt
./government/Post_Rate_Comm/Cohenetal_DeliveryCost.txt
./government/Post_Rate_Comm/Cohenetal_RuralDelivery.txt
./government/Post_Rate_Comm/Cohenetal_Scale.txt
./government/Post_Rate_Comm/Gleiman_EMASpeech.txt
./government/Post_Rate_Comm/Gleiman_gca2000.txt
./government/Post_Rate_Comm/Mitchell_6-17-Mit.txt
./government/Post_Rate_Comm/Mitchell_RMVancouver.txt
./government/Post_Rate_Comm/Mitchell_spyros-first-class.txt
./government/Post_Rate_Comm/Redacted_Study.txt
./government/Post_Rate_Comm/ReportToCongress2002WEB.txt
./government/Post_Rate_Comm/WolakSpeech_usps.txt
./plos/journal.pbio.0020001.txt
./plos/journal.pbio.0020010.txt
./plos/journal.pbio.0020012.txt
./plos/journal.pbio.0020013.txt
./plos/journal.pbio.0020019.txt
./plos/journal.pbio.0020028.txt
./plos/journal.pbio.0020035.txt
./plos/journal.pbio.0020040.txt
./plos/journal.pbio.0020042.txt
./plos/journal.pbio.0020043.txt
./plos/journal.pbio.0020046.txt
./plos/journal.pbio.0020047.txt
./plos/journal.pbio.0020052.txt
./plos/journal.pbio.0020053.txt
./plos/journal.pbio.0020054.txt
./plos/journal.pbio.0020063.txt
./plos/journal.pbio.0020064.txt
./plos/journal.pbio.0020067.txt
./plos/journal.pbio.0020068.txt
./plos/journal.pbio.0020071.txt
./plos/journal.pbio.0020073.txt
./plos/journal.pbio.0020100.txt
./plos/journal.pbio.0020101.txt
./plos/journal.pbio.0020105.txt
./plos/journal.pbio.0020112.txt
./plos/journal.pbio.0020113.txt
./plos/journal.pbio.0020116.txt
./plos/journal.pbio.0020121.txt
./plos/journal.pbio.0020125.txt
./plos/journal.pbio.0020127.txt
./plos/journal.pbio.0020133.txt
./plos/journal.pbio.0020140.txt
./plos/journal.pbio.0020145.txt
./plos/journal.pbio.0020146.txt
./plos/journal.pbio.0020147.txt
./plos/journal.pbio.0020148.txt
./plos/journal.pbio.0020150.txt
./plos/journal.pbio.0020156.txt
./plos/journal.pbio.0020161.txt
./plos/journal.pbio.0020164.txt
./plos/journal.pbio.0020169.txt
./plos/journal.pbio.0020172.txt
./plos/journal.pbio.0020183.txt
./plos/journal.pbio.0020187.txt
./plos/journal.pbio.0020190.txt
./plos/journal.pbio.0020206.txt
./plos/journal.pbio.0020213.txt
./plos/journal.pbio.0020214.txt
./plos/journal.pbio.0020215.txt
./plos/journal.pbio.0020216.txt
./plos/journal.pbio.0020223.txt
./plos/journal.pbio.0020224.txt
./plos/journal.pbio.0020228.txt
./plos/journal.pbio.0020232.txt
./plos/journal.pbio.0020241.txt
./plos/journal.pbio.0020262.txt
./plos/journal.pbio.0020263.txt
./plos/journal.pbio.0020267.txt
./plos/journal.pbio.0020272.txt
./plos/journal.pbio.0020276.txt
./plos/journal.pbio.0020297.txt
./plos/journal.pbio.0020302.txt
./plos/journal.pbio.0020306.txt
./plos/journal.pbio.0020307.txt
./plos/journal.pbio.0020310.txt
./plos/journal.pbio.0020311.txt
./plos/journal.pbio.0020337.txt
./plos/journal.pbio.0020346.txt
./plos/journal.pbio.0020347.txt
./plos/journal.pbio.0020348.txt
./plos/journal.pbio.0020350.txt
./plos/journal.pbio.0020353.txt
./plos/journal.pbio.0020354.txt
./plos/journal.pbio.0020394.txt
./plos/journal.pbio.0020400.txt
./plos/journal.pbio.0020401.txt
./plos/journal.pbio.0020404.txt
./plos/journal.pbio.0020406.txt
./plos/journal.pbio.0020419.txt
./plos/journal.pbio.0020420.txt
./plos/journal.pbio.0020430.txt
./plos/journal.pbio.0020431.txt
./plos/journal.pbio.0020439.txt
./plos/journal.pbio.0020440.txt
./plos/journal.pbio.0030021.txt
./plos/journal.pbio.0030024.txt
./plos/journal.pbio.0030032.txt
./plos/journal.pbio.0030050.txt
./plos/journal.pbio.0030051.txt
./plos/journal.pbio.0030056.txt
./plos/journal.pbio.0030062.txt
./plos/journal.pbio.0030065.txt
./plos/journal.pbio.0030076.txt
./plos/journal.pbio.0030094.txt
./plos/journal.pbio.0030097.txt
./plos/journal.pbio.0030102.txt
./plos/journal.pbio.0030105.txt
./plos/journal.pbio.0030127.txt
./plos/journal.pbio.0030129.txt
./plos/journal.pbio.0030131.txt
./plos/journal.pbio.0030136.txt
./plos/journal.pbio.0030137.txt
./plos/pmed.0010008.txt
./plos/pmed.0010010.txt
./plos/pmed.0010013.txt
./plos/pmed.0010021.txt
./plos/pmed.0010022.txt
./plos/pmed.0010023.txt
./plos/pmed.0010024.txt
./plos/pmed.0010025.txt
./plos/pmed.0010026.txt
./plos/pmed.0010028.txt
./plos/pmed.0010029.txt
./plos/pmed.0010030.txt
./plos/pmed.0010034.txt
./plos/pmed.0010036.txt
./plos/pmed.0010039.txt
./plos/pmed.0010041.txt
./plos/pmed.0010042.txt
./plos/pmed.0010045.txt
./plos/pmed.0010046.txt
./plos/pmed.0010047.txt
./plos/pmed.0010048.txt
./plos/pmed.0010049.txt
./plos/pmed.0010050.txt
./plos/pmed.0010051.txt
./plos/pmed.0010052.txt
./plos/pmed.0010056.txt
./plos/pmed.0010058.txt
./plos/pmed.0010060.txt
./plos/pmed.0010061.txt
./plos/pmed.0010062.txt
./plos/pmed.0010064.txt
./plos/pmed.0010066.txt
./plos/pmed.0010067.txt
./plos/pmed.0010068.txt
./plos/pmed.0010069.txt
./plos/pmed.0010070.txt
./plos/pmed.0010071.txt
./plos/pmed.0020002.txt
./plos/pmed.0020005.txt
./plos/pmed.0020007.txt
./plos/pmed.0020009.txt
./plos/pmed.0020015.txt
./plos/pmed.0020016.txt
./plos/pmed.0020017.txt
./plos/pmed.0020018.txt
./plos/pmed.0020019.txt
./plos/pmed.0020020.txt
./plos/pmed.0020021.txt
./plos/pmed.0020022.txt
./plos/pmed.0020023.txt
./plos/pmed.0020024.txt
./plos/pmed.0020027.txt
./plos/pmed.0020028.txt
./plos/pmed.0020033.txt
./plos/pmed.0020034.txt
./plos/pmed.0020035.txt
./plos/pmed.0020036.txt
./plos/pmed.0020039.txt
./plos/pmed.0020040.txt
./plos/pmed.0020045.txt
./plos/pmed.0020047.txt
./plos/pmed.0020048.txt
./plos/pmed.0020050.txt
./plos/pmed.0020055.txt
./plos/pmed.0020059.txt
./plos/pmed.0020060.txt
./plos/pmed.0020061.txt
./plos/pmed.0020062.txt
./plos/pmed.0020065.txt
./plos/pmed.0020067.txt
./plos/pmed.0020068.txt
./plos/pmed.0020071.txt
./plos/pmed.0020073.txt
./plos/pmed.0020074.txt
./plos/pmed.0020075.txt
./plos/pmed.0020082.txt
./plos/pmed.0020085.txt
./plos/pmed.0020086.txt
./plos/pmed.0020088.txt
./plos/pmed.0020090.txt
./plos/pmed.0020091.txt
./plos/pmed.0020094.txt
./plos/pmed.0020098.txt
./plos/pmed.0020099.txt
./plos/pmed.0020102.txt
./plos/pmed.0020103.txt
./plos/pmed.0020104.txt
./plos/pmed.0020113.txt
./plos/pmed.0020114.txt
./plos/pmed.0020115.txt
./plos/pmed.0020116.txt
./plos/pmed.0020117.txt
./plos/pmed.0020118.txt
./plos/pmed.0020120.txt
./plos/pmed.0020123.txt
./plos/pmed.0020140.txt
./plos/pmed.0020144.txt
./plos/pmed.0020145.txt
./plos/pmed.0020146.txt
./plos/pmed.0020148.txt
./plos/pmed.0020149.txt
./plos/pmed.0020150.txt
./plos/pmed.0020155.txt
./plos/pmed.0020157.txt
./plos/pmed.0020158.txt
./plos/pmed.0020160.txt
./plos/pmed.0020161.txt
./plos/pmed.0020162.txt
./plos/pmed.0020180.txt
./plos/pmed.0020181.txt
./plos/pmed.0020182.txt
./plos/pmed.0020187.txt
./plos/pmed.0020189.txt
./plos/pmed.0020191.txt
./plos/pmed.0020192.txt
./plos/pmed.0020194.txt
./plos/pmed.0020195.txt
./plos/pmed.0020196.txt
./plos/pmed.0020197.txt
./plos/pmed.0020198.txt
./plos/pmed.0020200.txt
./plos/pmed.0020201.txt
./plos/pmed.0020203.txt
./plos/pmed.0020206.txt
./plos/pmed.0020208.txt
./plos/pmed.0020209.txt
./plos/pmed.0020210.txt
./plos/pmed.0020212.txt
./plos/pmed.0020216.txt
./plos/pmed.0020226.txt
./plos/pmed.0020231.txt
./plos/pmed.0020232.txt
./plos/pmed.0020235.txt
./plos/pmed.0020236.txt
./plos/pmed.0020237.txt
./plos/pmed.0020238.txt
./plos/pmed.0020239.txt
./plos/pmed.0020242.txt
./plos/pmed.0020246.txt
./plos/pmed.0020247.txt
./plos/pmed.0020249.txt
./plos/pmed.0020257.txt
./plos/pmed.0020258.txt
./plos/pmed.0020268.txt
./plos/pmed.0020272.txt
./plos/pmed.0020273.txt
./plos/pmed.0020274.txt
./plos/pmed.0020275.txt
./plos/pmed.0020278.txt
./plos/pmed.0020281.txt
```
* The `-type` option after `find` lists out all types of files, directories, links, etc. depending on the argument given after the option (e.g. `d` lists out all directories). This could be really helpful as another more direct way of listing out what's inside a directory as opposed to individually using the `ls` and `cd` commands, especially if you're specifically looking for just all possible directories or the total number of files, for instance. It should be noted the `find -type f` command was cropped out of the terminal alongside other possible files within the `technical` directory.

```
$ find 911report -ls
3659174697678334      4 drwxr-xr-x   1 kurom    197609          0 Apr 30 13:17 911report
2814749767546368    120 -rw-r--r--   1 kurom    197609     119387 Apr 30 13:17 911report/chapter-1.txt
4222124651099657     48 -rw-r--r--   1 kurom    197609      47910 Apr 30 13:17 911report/chapter-10.txt
3096224744257036     72 -rw-r--r--   1 kurom    197609      71968 Apr 30 13:17 911report/chapter-11.txt
2814749767546383    128 -rw-r--r--   1 kurom    197609     129126 Apr 30 13:17 911report/chapter-12.txt
7881299348338193     92 -rw-r--r--   1 kurom    197609      90943 Apr 30 13:17 911report/chapter-13.1.txt
5066549581231635    112 -rw-r--r--   1 kurom    197609     111804 Apr 30 13:17 911report/chapter-13.2.txt
2814749767546388    152 -rw-r--r--   1 kurom    197609     152185 Apr 30 13:17 911report/chapter-13.3.txt
3659174697678361    264 -rw-r--r--   1 kurom    197609     268853 Apr 30 13:17 911report/chapter-13.4.txt
3096224744257051    288 -rw-r--r--   1 kurom    197609     294230 Apr 30 13:17 911report/chapter-13.5.txt
3377699720967711     80 -rw-r--r--   1 kurom    197609      80751 Apr 30 13:17 911report/chapter-2.txt
3377699720967713    264 -rw-r--r--   1 kurom    197609     267519 Apr 30 13:17 911report/chapter-3.txt
4222124651099686    100 -rw-r--r--   1 kurom    197609     100212 Apr 30 13:17 911report/chapter-5.txt
3096224744257088    148 -rw-r--r--   1 kurom    197609     150961 Apr 30 13:17 911report/chapter-6.txt
3659174697678406    128 -rw-r--r--   1 kurom    197609     129949 Apr 30 13:17 911report/chapter-7.txt
3377699720967798     84 -rw-r--r--   1 kurom    197609      85871 Apr 30 13:17 911report/chapter-8.txt
5910974511363721    148 -rw-r--r--   1 kurom    197609     151529 Apr 30 13:17 911report/chapter-9.txt
3377699720967828     12 -rw-r--r--   1 kurom    197609       9440 Apr 30 13:17 911report/preface.txt
```
```
$ find government -ls
3096224744296952      4 drwxr-xr-x   1 kurom    197609          0 Apr 30 13:17 government
2814749767586300      8 drwxr-xr-x   1 kurom    197609          0 Apr 30 13:17 government/About_LSC
1688849860743681     24 -rw-r--r--   1 kurom    197609      20530 Apr 30 13:17 government/About_LSC/Comments_on_semiannual.txt
3940649674428983    224 -rw-r--r--   1 kurom    197609     227212 Apr 30 13:17 government/About_LSC/commission_report.txt
2533274790875708     16 -rw-r--r--   1 kurom    197609      14195 Apr 30 13:17 government/About_LSC/conference_highlights.txt
1688849860743680     16 -rw-r--r--   1 kurom    197609      13889 Apr 30 13:17 government/About_LSC/CONFIG_STANDARDS.txt
3377699721007677     24 -rw-r--r--   1 kurom    197609      24017 Apr 30 13:17 government/About_LSC/diversity_priorities.txt
2533274790875653     28 -rw-r--r--   1 kurom    197609      28590 Apr 30 13:17 government/About_LSC/LegalServCorp_v_VelazquezDissent.txt
2814749767586311     28 -rw-r--r--   1 kurom    197609      27571 Apr 30 13:17 government/About_LSC/LegalServCorp_v_VelazquezOpinion.txt
3940649674428948      8 -rw-r--r--   1 kurom    197609       7222 Apr 30 13:17 government/About_LSC/LegalServCorp_v_VelazquezSyllabus.txt
3377699721007637      8 -rw-r--r--   1 kurom    197609       6248 Apr 30 13:17 government/About_LSC/ODonnell_et_al_v_LSCdecision.txt
2533274790875674     36 -rw-r--r--   1 kurom    197609      34614 Apr 30 13:17 government/About_LSC/ONTARIO_LEGAL_AID_SERIES.txt
3377699721007645     48 -rw-r--r--   1 kurom    197609      49122 Apr 30 13:17 government/About_LSC/Progress_report.txt
3377699721007648     16 -rw-r--r--   1 kurom    197609      13967 Apr 30 13:17 government/About_LSC/Protocol_Regarding_Access.txt
3096224744297024     20 -rw-r--r--   1 kurom    197609      18114 Apr 30 13:17 government/About_LSC/reporting_system.txt
2814749767586339     44 -rw-r--r--   1 kurom    197609      42167 Apr 30 13:17 government/About_LSC/Special_report_to_congress.txt
3377699721007657    152 -rw-r--r--   1 kurom    197609     155337 Apr 30 13:17 government/About_LSC/State_Planning_Report.txt
3096224744297007     32 -rw-r--r--   1 kurom    197609      30519 Apr 30 13:17 government/About_LSC/State_Planning_Special_Report.txt
1688849860743733     68 -rw-r--r--   1 kurom    197609      69007 Apr 30 13:17 government/About_LSC/Strategic_report.txt
3096224744297028      4 drwxr-xr-x   1 kurom    197609          0 Apr 30 13:17 government/Alcohol_Problems
4222124651139657     32 -rw-r--r--   1 kurom    197609      32413 Apr 30 13:17 government/Alcohol_Problems/DraftRecom-PDF.txt
3096224744297036     36 -rw-r--r--   1 kurom    197609      36564 Apr 30 13:17 government/Alcohol_Problems/Session2-PDF.txt
3096224744297041     96 -rw-r--r--   1 kurom    197609      95891 Apr 30 13:17 government/Alcohol_Problems/Session3-PDF.txt
3096224744297042     80 -rw-r--r--   1 kurom    197609      81409 Apr 30 13:17 government/Alcohol_Problems/Session4-PDF.txt
3096224744297051      4 drwxr-xr-x   1 kurom    197609          0 Apr 30 13:17 government/Env_Prot_Agen
3659174697718364     20 -rw-r--r--   1 kurom    197609      20435 Apr 30 13:17 government/Env_Prot_Agen/1-3_meth_901.txt
2533274790875745     76 -rw-r--r--   1 kurom    197609      74808 Apr 30 13:17 government/Env_Prot_Agen/atx1-6.txt
3659174697718370    248 -rw-r--r--   1 kurom    197609     250925 Apr 30 13:17 government/Env_Prot_Agen/bill.txt
2533274790875754     76 -rw-r--r--   1 kurom    197609      76081 Apr 30 13:17 government/Env_Prot_Agen/ctf1-6.txt
2814749767586415     80 -rw-r--r--   1 kurom    197609      80231 Apr 30 13:17 government/Env_Prot_Agen/ctf7-10.txt
2533274790875762    136 -rw-r--r--   1 kurom    197609     135728 Apr 30 13:17 government/Env_Prot_Agen/ctm4-10.txt
2814749767586419     36 -rw-r--r--   1 kurom    197609      33506 Apr 30 13:17 government/Env_Prot_Agen/final.txt
2533274790875766     64 -rw-r--r--   1 kurom    197609      63613 Apr 30 13:17 government/Env_Prot_Agen/jeffordslieberm.txt
2814749767586423    196 -rw-r--r--   1 kurom    197609     199381 Apr 30 13:17 government/Env_Prot_Agen/multi102902.txt
2533274790875771     32 -rw-r--r--   1 kurom    197609      31944 Apr 30 13:17 government/Env_Prot_Agen/nov1.txt
2814749767586434     20 -rw-r--r--   1 kurom    197609      20179 Apr 30 13:17 government/Env_Prot_Agen/ro_clear_skies_book.txt
6192449488114343     56 -rw-r--r--   1 kurom    197609      53461 Apr 30 13:17 government/Env_Prot_Agen/section-by-section_summary.txt
4503599627850410    180 -rw-r--r--   1 kurom    197609     181744 Apr 30 13:17 government/Env_Prot_Agen/tech_adden.txt
1688849860743855     16 -rw-r--r--   1 kurom    197609      13534 Apr 30 13:17 government/Env_Prot_Agen/tech_sectiong.txt
1688849860743856     24 drwxr-xr-x   1 kurom    197609          0 Apr 30 13:17 government/Gen_Account_Office
3096224744297207    100 -rw-r--r--   1 kurom    197609      99891 Apr 30 13:17 government/Gen_Account_Office/ai00134.txt
2251799814165243     72 -rw-r--r--   1 kurom    197609      71685 Apr 30 13:17 government/Gen_Account_Office/ai2132.txt
2251799814165244    116 -rw-r--r--   1 kurom    197609     116585 Apr 30 13:17 government/Gen_Account_Office/ai9868.txt
3377699721007871      8 -rw-r--r--   1 kurom    197609       4305 Apr 30 13:17 government/Gen_Account_Office/d01121g.txt
3096224744297216     24 -rw-r--r--   1 kurom    197609      24358 Apr 30 13:17 government/Gen_Account_Office/d01145g.txt
1688849860743939     36 -rw-r--r--   1 kurom    197609      35061 Apr 30 13:17 government/Gen_Account_Office/d01186g.txt
1688849860743940    140 -rw-r--r--   1 kurom    197609     140413 Apr 30 13:17 government/Gen_Account_Office/d01376g.txt
1688849860743942    304 -rw-r--r--   1 kurom    197609     307735 Apr 30 13:17 government/Gen_Account_Office/d01591sp.txt
1688849860743943    128 -rw-r--r--   1 kurom    197609     130078 Apr 30 13:17 government/Gen_Account_Office/d0269g.txt
1688849860743946    140 -rw-r--r--   1 kurom    197609     142742 Apr 30 13:17 government/Gen_Account_Office/d02701.txt
1688849860743947     60 -rw-r--r--   1 kurom    197609      60328 Apr 30 13:17 government/Gen_Account_Office/d03232sp.txt
3096224744297228     48 -rw-r--r--   1 kurom    197609      48671 Apr 30 13:17 government/Gen_Account_Office/d03273g.txt
3096224744297231     68 -rw-r--r--   1 kurom    197609      69510 Apr 30 13:17 government/Gen_Account_Office/d03419sp.txt
1688849860743952     28 -rw-r--r--   1 kurom    197609      27445 Apr 30 13:17 government/Gen_Account_Office/ffm.txt
1688849860743953    108 -rw-r--r--   1 kurom    197609     108889 Apr 30 13:17 government/Gen_Account_Office/gg96118.txt
3096224744297139    248 -rw-r--r--   1 kurom    197609     252219 Apr 30 13:17 government/Gen_Account_Office/GovernmentAuditingStandards_yb2002ed.txt
3377699721007892    120 -rw-r--r--   1 kurom    197609     119921 Apr 30 13:17 government/Gen_Account_Office/im814.txt
3096224744297140     32 -rw-r--r--   1 kurom    197609      28945 Apr 30 13:17 government/Gen_Account_Office/InternalControl_ai00021p.txt
2251799814165175     84 -rw-r--r--   1 kurom    197609      82331 Apr 30 13:17 government/Gen_Account_Office/July11-2001_gg00172r.txt
3096224744297145     56 -rw-r--r--   1 kurom    197609      53562 Apr 30 13:17 government/Gen_Account_Office/June30-2000_gg00135r.txt
3096224744297155     32 -rw-r--r--   1 kurom    197609      30052 Apr 30 13:17 government/Gen_Account_Office/Letter_Walkeraug17let.txt
2251799814165184      8 -rw-r--r--   1 kurom    197609       7994 Apr 30 13:17 government/Gen_Account_Office/Letter_WalkerJan30-2001.txt
3096224744297162    116 -rw-r--r--   1 kurom    197609     116585 Apr 30 13:17 government/Gen_Account_Office/May1998_ai98068.txt
3096224744297170     40 -rw-r--r--   1 kurom    197609      36907 Apr 30 13:17 government/Gen_Account_Office/Oct15-1999_gg00026t.txt
3377699721007834     76 -rw-r--r--   1 kurom    197609      74910 Apr 30 13:17 government/Gen_Account_Office/Oct15-2001_d0224.txt
3096224744297237      8 -rw-r--r--   1 kurom    197609       6953 Apr 30 13:17 government/Gen_Account_Office/og96009.txt
3096224744297244     20 -rw-r--r--   1 kurom    197609      16639 Apr 30 13:17 government/Gen_Account_Office/og96011.txt
3096224744297245     12 -rw-r--r--   1 kurom    197609      10827 Apr 30 13:17 government/Gen_Account_Office/og96012.txt
1688849860743969     12 -rw-r--r--   1 kurom    197609       9482 Apr 30 13:17 government/Gen_Account_Office/og96014.txt
1688849860743970      8 -rw-r--r--   1 kurom    197609       6131 Apr 30 13:17 government/Gen_Account_Office/og96015.txt
1688849860743972     12 -rw-r--r--   1 kurom    197609       8872 Apr 30 13:17 government/Gen_Account_Office/og96020.txt
1688849860743973      8 -rw-r--r--   1 kurom    197609       7117 Apr 30 13:17 government/Gen_Account_Office/og96021.txt
1688849860743974     16 -rw-r--r--   1 kurom    197609      14965 Apr 30 13:17 government/Gen_Account_Office/og96022.txt
1688849860743975     12 -rw-r--r--   1 kurom    197609       9998 Apr 30 13:17 government/Gen_Account_Office/og96023.txt
1688849860743976     16 -rw-r--r--   1 kurom    197609      14551 Apr 30 13:17 government/Gen_Account_Office/og96026.txt
1688849860743977     12 -rw-r--r--   1 kurom    197609      11529 Apr 30 13:17 government/Gen_Account_Office/og96027.txt
3096224744297260      8 -rw-r--r--   1 kurom    197609       7943 Apr 30 13:17 government/Gen_Account_Office/og96028.txt
3377699721007917     12 -rw-r--r--   1 kurom    197609      10658 Apr 30 13:17 government/Gen_Account_Office/og96031.txt
3377699721007923     12 -rw-r--r--   1 kurom    197609       9083 Apr 30 13:17 government/Gen_Account_Office/og96032.txt
3096224744297268      8 -rw-r--r--   1 kurom    197609       6742 Apr 30 13:17 government/Gen_Account_Office/og96033.txt
3096224744297277     12 -rw-r--r--   1 kurom    197609      10571 Apr 30 13:17 government/Gen_Account_Office/og96034.txt
3096224744297278     16 -rw-r--r--   1 kurom    197609      12689 Apr 30 13:17 government/Gen_Account_Office/og96036.txt
3096224744297287     12 -rw-r--r--   1 kurom    197609       9346 Apr 30 13:17 government/Gen_Account_Office/og96037.txt
3377699721007944     20 -rw-r--r--   1 kurom    197609      16443 Apr 30 13:17 government/Gen_Account_Office/og96038.txt
1688849860744011     12 -rw-r--r--   1 kurom    197609       9903 Apr 30 13:17 government/Gen_Account_Office/og96040.txt
1688849860744012     20 -rw-r--r--   1 kurom    197609      16930 Apr 30 13:17 government/Gen_Account_Office/og96041.txt
3096224744297296     12 -rw-r--r--   1 kurom    197609       9149 Apr 30 13:17 government/Gen_Account_Office/og96042.txt
3377699721007959     12 -rw-r--r--   1 kurom    197609      10893 Apr 30 13:17 government/Gen_Account_Office/og96043.txt
3377699721007962     12 -rw-r--r--   1 kurom    197609      10559 Apr 30 13:17 government/Gen_Account_Office/og96045.txt
3096224744297308     12 -rw-r--r--   1 kurom    197609       9997 Apr 30 13:17 government/Gen_Account_Office/og96047.txt
3096224744297312      8 -rw-r--r--   1 kurom    197609       7040 Apr 30 13:17 government/Gen_Account_Office/og97001.txt
2251799814165347      8 -rw-r--r--   1 kurom    197609       6899 Apr 30 13:17 government/Gen_Account_Office/og97002.txt
2251799814165351     12 -rw-r--r--   1 kurom    197609      11479 Apr 30 13:17 government/Gen_Account_Office/og97003.txt
3096224744297320     12 -rw-r--r--   1 kurom    197609       8331 Apr 30 13:17 government/Gen_Account_Office/og97011.txt
3096224744297329      8 -rw-r--r--   1 kurom    197609       6648 Apr 30 13:17 government/Gen_Account_Office/og97019.txt
3377699721007987     12 -rw-r--r--   1 kurom    197609       8685 Apr 30 13:17 government/Gen_Account_Office/og97020.txt
3377699721007990      8 -rw-r--r--   1 kurom    197609       6964 Apr 30 13:17 government/Gen_Account_Office/og97023.txt
3096224744297336      8 -rw-r--r--   1 kurom    197609       5953 Apr 30 13:17 government/Gen_Account_Office/og97028.txt
2251799814165372     12 -rw-r--r--   1 kurom    197609      11600 Apr 30 13:17 government/Gen_Account_Office/og97032.txt
2251799814165373      8 -rw-r--r--   1 kurom    197609       8130 Apr 30 13:17 government/Gen_Account_Office/og97038.txt
3377699721008001     12 -rw-r--r--   1 kurom    197609      10026 Apr 30 13:17 government/Gen_Account_Office/og97039.txt
3096224744297346     12 -rw-r--r--   1 kurom    197609      11331 Apr 30 13:17 government/Gen_Account_Office/og97041.txt
3096224744297352     12 -rw-r--r--   1 kurom    197609      10818 Apr 30 13:17 government/Gen_Account_Office/og97043.txt
3096224744297354      8 -rw-r--r--   1 kurom    197609       7613 Apr 30 13:17 government/Gen_Account_Office/og97045.txt
3096224744297360      8 -rw-r--r--   1 kurom    197609       7695 Apr 30 13:17 government/Gen_Account_Office/og97046.txt
3377699721008017     12 -rw-r--r--   1 kurom    197609      11494 Apr 30 13:17 government/Gen_Account_Office/og97050.txt
3096224744297365     12 -rw-r--r--   1 kurom    197609       9526 Apr 30 13:17 government/Gen_Account_Office/og97051.txt
3377699721008027     12 -rw-r--r--   1 kurom    197609      10190 Apr 30 13:17 government/Gen_Account_Office/og97052.txt
3377699721008030      8 -rw-r--r--   1 kurom    197609       6071 Apr 30 13:17 government/Gen_Account_Office/og98018.txt
1688849860744097      8 -rw-r--r--   1 kurom    197609       5492 Apr 30 13:17 government/Gen_Account_Office/og98019.txt
1688849860744098     12 -rw-r--r--   1 kurom    197609      10703 Apr 30 13:17 government/Gen_Account_Office/og98022.txt
3096224744297381      8 -rw-r--r--   1 kurom    197609       7106 Apr 30 13:17 government/Gen_Account_Office/og98024.txt
1688849860744106      8 -rw-r--r--   1 kurom    197609       5661 Apr 30 13:17 government/Gen_Account_Office/og98026.txt
1688849860744107      8 -rw-r--r--   1 kurom    197609       5577 Apr 30 13:17 government/Gen_Account_Office/og98029.txt
3377699721008045      8 -rw-r--r--   1 kurom    197609       6275 Apr 30 13:17 government/Gen_Account_Office/og98030.txt
3096224744297390     12 -rw-r--r--   1 kurom    197609       8752 Apr 30 13:17 government/Gen_Account_Office/og98032.txt
3096224744297395     12 -rw-r--r--   1 kurom    197609       8712 Apr 30 13:17 government/Gen_Account_Office/og98040.txt
3096224744297397      8 -rw-r--r--   1 kurom    197609       7070 Apr 30 13:17 government/Gen_Account_Office/og98041.txt
3096224744297401      8 -rw-r--r--   1 kurom    197609       6102 Apr 30 13:17 government/Gen_Account_Office/og98044.txt
3377699721008058     12 -rw-r--r--   1 kurom    197609       9101 Apr 30 13:17 government/Gen_Account_Office/og98045.txt
3096224744297410      8 -rw-r--r--   1 kurom    197609       7250 Apr 30 13:17 government/Gen_Account_Office/og98046.txt
1688849860744134      8 -rw-r--r--   1 kurom    197609       6717 Apr 30 13:17 government/Gen_Account_Office/og99036.txt
3096224744297180     52 -rw-r--r--   1 kurom    197609      50773 Apr 30 13:17 government/Gen_Account_Office/Paper_Walker11-2002_acpro122.txt
1688849860744135    204 -rw-r--r--   1 kurom    197609     206294 Apr 30 13:17 government/Gen_Account_Office/pe1019.txt
3096224744297186     68 -rw-r--r--   1 kurom    197609      67189 Apr 30 13:17 government/Gen_Account_Office/Sept14-2002_d011070.txt
3096224744297188    116 -rw-r--r--   1 kurom    197609     115793 Apr 30 13:17 government/Gen_Account_Office/Sept27-2002_d02966.txt
3096224744297192    308 -rw-r--r--   1 kurom    197609     312125 Apr 30 13:17 government/Gen_Account_Office/Statements_Feb28-1997_volume.txt
3096224744297200     96 -rw-r--r--   1 kurom    197609      98157 Apr 30 13:17 government/Gen_Account_Office/Testimony_cg00010t.txt
3096224744297205     40 -rw-r--r--   1 kurom    197609      39330 Apr 30 13:17 government/Gen_Account_Office/Testimony_d01609t.txt
3377699721007849     40 -rw-r--r--   1 kurom    197609      38014 Apr 30 13:17 government/Gen_Account_Office/Testimony_Jul15-2002_d02940t.txt
3377699721007855     64 -rw-r--r--   1 kurom    197609      63280 Apr 30 13:17 government/Gen_Account_Office/Testimony_Jul17-2002_d02957t.txt
3377699721008073     64 drwxr-xr-x   1 kurom    197609          0 Apr 30 13:17 government/Media
3377699721008076      4 -rw-r--r--   1 kurom    197609       3095 Apr 30 13:17 government/Media/5_Legal_Groups.txt
2251799814165471      8 -rw-r--r--   1 kurom    197609       6382 Apr 30 13:17 government/Media/Abuse_penalties.txt
3096224744297441      4 -rw-r--r--   1 kurom    197609       2933 Apr 30 13:17 government/Media/Advocate_for_Poor.txt
2251799814165783      4 -rw-r--r--   1 kurom    197609       2670 Apr 30 13:17 government/Media/agency_expands.txt
3377699721008100      4 -rw-r--r--   1 kurom    197609       2909 Apr 30 13:17 government/Media/Aid_Gets_7_Million.txt
3096224744297445      4 -rw-r--r--   1 kurom    197609       2228 Apr 30 13:17 government/Media/All_May_Have_Justice.txt
3096224744297449      8 -rw-r--r--   1 kurom    197609       4960 Apr 30 13:17 government/Media/Annual_Fee.txt
1688849860744170      8 -rw-r--r--   1 kurom    197609       6062 Apr 30 13:17 government/Media/Anthem_Payout.txt
2251799814165454      4 -rw-r--r--   1 kurom    197609       2453 Apr 30 13:17 government/Media/AP_LawSchoolDebts.txt
1688849860744171     12 -rw-r--r--   1 kurom    197609      11176 Apr 30 13:17 government/Media/Assuring_Underprivileged.txt
3096224744297452      4 -rw-r--r--   1 kurom    197609       2300 Apr 30 13:17 government/Media/Attorney_gives_his_time.txt
3377699721008115      8 -rw-r--r--   1 kurom    197609       7523 Apr 30 13:17 government/Media/Avoids_Budget_Cut.txt
3096224744297435      8 -rw-r--r--   1 kurom    197609       7299 Apr 30 13:17 government/Media/A_helping_hand.txt
3096224744297427      4 -rw-r--r--   1 kurom    197609       2232 Apr 30 13:17 government/Media/A_Perk_of_Age.txt
3096224744297755      8 -rw-r--r--   1 kurom    197609       4365 Apr 30 13:17 government/Media/balance_scales_of_justice.txt
3096224744297464      8 -rw-r--r--   1 kurom    197609       4631 Apr 30 13:17 government/Media/Barnes_new_job.txt
3096224744297465      4 -rw-r--r--   1 kurom    197609       2291 Apr 30 13:17 government/Media/Barnes_pro_bono.txt
2251799814165493      4 -rw-r--r--   1 kurom    197609       2202 Apr 30 13:17 government/Media/Barnes_Volunteers.txt
1688849860744189      4 -rw-r--r--   1 kurom    197609       4031 Apr 30 13:17 government/Media/Barr_sharpening_ax.txt
1688849860744190      8 -rw-r--r--   1 kurom    197609       7657 Apr 30 13:17 government/Media/BergenCountyRecord.txt
3377699721008131      4 -rw-r--r--   1 kurom    197609       2206 Apr 30 13:17 government/Media/Bias_on_the_Job.txt
2251799814165510      4 -rw-r--r--   1 kurom    197609       2156 Apr 30 13:17 government/Media/Boone_legal_service.txt
3096224744297483      8 -rw-r--r--   1 kurom    197609       5546 Apr 30 13:17 government/Media/Bridging_legal_aid_gap.txt
3377699721008140      8 -rw-r--r--   1 kurom    197609       5721 Apr 30 13:17 government/Media/BusinessWire.txt
3096224744297492      4 -rw-r--r--   1 kurom    197609       2477 Apr 30 13:17 government/Media/BusinessWire2.txt
3096224744297497      4 -rw-r--r--   1 kurom    197609       3530 Apr 30 13:17 government/Media/Butler_Co_attorneys.txt
3377699721008157      4 -rw-r--r--   1 kurom    197609       1750 Apr 30 13:17 government/Media/Campaign_Pays.txt
3096224744297502      8 -rw-r--r--   1 kurom    197609       6226 Apr 30 13:17 government/Media/City_Council_Budget.txt
1688849860744225      4 -rw-r--r--   1 kurom    197609       2470 Apr 30 13:17 government/Media/Civil_Matters.txt
1688849860744226      8 -rw-r--r--   1 kurom    197609       6491 Apr 30 13:17 government/Media/CommercialAppealMemphis2.txt
3096224744297514      4 -rw-r--r--   1 kurom    197609       2362 Apr 30 13:17 government/Media/Commercial_Appeal.txt
3096224744297518     16 -rw-r--r--   1 kurom    197609      14708 Apr 30 13:17 government/Media/Coup_Reshapes_Legal_Aid.txt
3096224744297526      4 -rw-r--r--   1 kurom    197609       1983 Apr 30 13:17 government/Media/Court_Keeps_Judge_From.txt
3377699721008184      4 -rw-r--r--   1 kurom    197609       3829 Apr 30 13:17 government/Media/Crains_New_York_Business.txt
3377699721008412      4 -rw-r--r--   1 kurom    197609       3773 Apr 30 13:17 government/Media/defend_yourself.txt
2251799814165565      4 -rw-r--r--   1 kurom    197609       3616 Apr 30 13:17 government/Media/Disaster_center.txt
2251799814165567      4 -rw-r--r--   1 kurom    197609       2409 Apr 30 13:17 government/Media/Do-it-yourself_divorce.txt
3096224744297540      4 -rw-r--r--   1 kurom    197609       3849 Apr 30 13:17 government/Media/Domestic_violence_aid.txt
3377699721008194      8 -rw-r--r--   1 kurom    197609       5263 Apr 30 13:17 government/Media/Domestic_Violence_Ruling.txt
1688849860744263      4 -rw-r--r--   1 kurom    197609       3044 Apr 30 13:17 government/Media/Donald_Hilliker.txt
1688849860744264      8 -rw-r--r--   1 kurom    197609       4454 Apr 30 13:17 government/Media/Entities_Merge.txt
3096224744297550      8 -rw-r--r--   1 kurom    197609       4105 Apr 30 13:17 government/Media/Eviction_law.txt
3096224744297761      4 -rw-r--r--   1 kurom    197609       3104 Apr 30 13:17 government/Media/families_saved.txt
3377699721008213     12 -rw-r--r--   1 kurom    197609       9739 Apr 30 13:17 government/Media/Farm_workers.txt
3096224744297559      4 -rw-r--r--   1 kurom    197609       3859 Apr 30 13:17 government/Media/Federal_agency.txt
3096224744297568      8 -rw-r--r--   1 kurom    197609       5689 Apr 30 13:17 government/Media/Few_who_need.txt
3377699721008420      4 -rw-r--r--   1 kurom    197609       2864 Apr 30 13:17 government/Media/fight_domestic_abuse.txt
1688849860744291      4 -rw-r--r--   1 kurom    197609       1801 Apr 30 13:17 government/Media/Fire_Victims_Sue.txt
1688849860744292      4 -rw-r--r--   1 kurom    197609       3639 Apr 30 13:17 government/Media/Firm_to_the_Poor_Needs_Help.txt
3096224744297574      4 -rw-r--r--   1 kurom    197609       3743 Apr 30 13:17 government/Media/FortWorthStarTelegram.txt
2251799814165612      8 -rw-r--r--   1 kurom    197609       5368 Apr 30 13:17 government/Media/Free_Legal_Assistance.txt
2251799814165613      4 -rw-r--r--   1 kurom    197609       2762 Apr 30 13:17 government/Media/Free_legal_service.txt
2251799814165618      4 -rw-r--r--   1 kurom    197609       2126 Apr 30 13:17 government/Media/Funding_cuts_force.txt
2251799814165617      4 -rw-r--r--   1 kurom    197609       3204 Apr 30 13:17 government/Media/Funding_May_Limit.txt
2251799814165621      8 -rw-r--r--   1 kurom    197609       4164 Apr 30 13:17 government/Media/Funds_Shortage.txt
2251799814165585      4 -rw-r--r--   1 kurom    197609       2572 Apr 30 13:17 government/Media/FY_04_Budget_Outlook.txt
2251799814165622      4 -rw-r--r--   1 kurom    197609       3199 Apr 30 13:17 government/Media/Ginny_Kilgore.txt
2251799814165625      8 -rw-r--r--   1 kurom    197609       7092 Apr 30 13:17 government/Media/Good_guys_reward.txt
1688849860744489      8 -rw-r--r--   1 kurom    197609       5515 Apr 30 13:17 government/Media/grants_fail_to_come.txt
2251799814165626      8 -rw-r--r--   1 kurom    197609       7430 Apr 30 13:17 government/Media/Greedy_Generous.txt
2251799814165629      8 -rw-r--r--   1 kurom    197609       5544 Apr 30 13:17 government/Media/GreensburgDailyNews.txt
2251799814165630      4 -rw-r--r--   1 kurom    197609       3780 Apr 30 13:17 government/Media/Hard_to_Get.txt
2251799814165633      4 -rw-r--r--   1 kurom    197609       2056 Apr 30 13:17 government/Media/Helping_Hands.txt
2251799814165634      8 -rw-r--r--   1 kurom    197609       6398 Apr 30 13:17 government/Media/Helping_Out.txt
1688849860744490      4 -rw-r--r--   1 kurom    197609       3789 Apr 30 13:17 government/Media/help_rent-to-own_tenants.txt
2251799814165638      4 -rw-r--r--   1 kurom    197609       2388 Apr 30 13:17 government/Media/Higher_court.txt
2251799814165637      4 -rw-r--r--   1 kurom    197609       3817 Apr 30 13:17 government/Media/Higher_Registration_Fees.txt
3377699721008428      8 -rw-r--r--   1 kurom    197609       4192 Apr 30 13:17 government/Media/highlight_Senior_Day.txt
2251799814165641      8 -rw-r--r--   1 kurom    197609       7862 Apr 30 13:17 government/Media/IOLTA_INTEREST_RATE.txt
2251799814165642      4 -rw-r--r--   1 kurom    197609       2048 Apr 30 13:17 government/Media/It_Pays_to_Know.txt
2251799814165645      8 -rw-r--r--   1 kurom    197609       5561 Apr 30 13:17 government/Media/Justice_for_all.txt
2251799814165646      4 -rw-r--r--   1 kurom    197609       1782 Apr 30 13:17 government/Media/Justice_requests.txt
2251799814165649      4 -rw-r--r--   1 kurom    197609       3377 Apr 30 13:17 government/Media/Kiosks_for_court_forms.txt
2251799814165651      4 -rw-r--r--   1 kurom    197609       3977 Apr 30 13:17 government/Media/Law-school_grads.txt
3377699721008284      4 -rw-r--r--   1 kurom    197609       2036 Apr 30 13:17 government/Media/Lawyer_Web_Survey.txt
2251799814165656      4 -rw-r--r--   1 kurom    197609       3685 Apr 30 13:17 government/Media/Law_Award_from_College.txt
2251799814165657     12 -rw-r--r--   1 kurom    197609       8684 Apr 30 13:17 government/Media/Law_Schools.txt
3096224744297629      8 -rw-r--r--   1 kurom    197609       6088 Apr 30 13:17 government/Media/Legal-aid_chief.txt
3096224744297635      4 -rw-r--r--   1 kurom    197609       3669 Apr 30 13:17 government/Media/Legal_Aid_attorney.txt
3096224744297639      4 -rw-r--r--   1 kurom    197609       2914 Apr 30 13:17 government/Media/Legal_Aid_campaign.txt
3377699721008296      4 -rw-r--r--   1 kurom    197609       3970 Apr 30 13:17 government/Media/Legal_Aid_in_Clay_County.txt
3096224744297643      4 -rw-r--r--   1 kurom    197609       2909 Apr 30 13:17 government/Media/Legal_Aid_looks_to_legislators.txt
3377699721008290      4 -rw-r--r--   1 kurom    197609       2142 Apr 30 13:17 government/Media/Legal_Aid_Society.txt
3377699721008302      4 -rw-r--r--   1 kurom    197609       2849 Apr 30 13:17 government/Media/Legal_hotline.txt
2251799814165683      8 -rw-r--r--   1 kurom    197609       4129 Apr 30 13:17 government/Media/Legal_services_for_poor.txt
2251799814165684      8 -rw-r--r--   1 kurom    197609       7353 Apr 30 13:17 government/Media/Legal_system_fails_poor.txt
3096224744297774      4 -rw-r--r--   1 kurom    197609       3204 Apr 30 13:17 government/Media/less_legal_aid.txt
2251799814165688      8 -rw-r--r--   1 kurom    197609       4755 Apr 30 13:17 government/Media/Library_Lawyers.txt
2251799814165689      8 -rw-r--r--   1 kurom    197609       4644 Apr 30 13:17 government/Media/Lindsays_legacy.txt
2251799814165693      8 -rw-r--r--   1 kurom    197609       7029 Apr 30 13:17 government/Media/Local_Attorneys.txt
2251799814165694      4 -rw-r--r--   1 kurom    197609       3735 Apr 30 13:17 government/Media/Lockyer_Warns.txt
2251799814165697      4 -rw-r--r--   1 kurom    197609       2776 Apr 30 13:17 government/Media/Low-income_children.txt
2251799814165698      8 -rw-r--r--   1 kurom    197609       6846 Apr 30 13:17 government/Media/Major_Changes.txt
2251799814165701      8 -rw-r--r--   1 kurom    197609       5965 Apr 30 13:17 government/Media/Making_a_case.txt
2251799814165811      8 -rw-r--r--   1 kurom    197609       5791 Apr 30 13:17 government/Media/man_on_national_team.txt
2251799814165702      8 -rw-r--r--   1 kurom    197609       7877 Apr 30 13:17 government/Media/Marylands_Legal_Aid.txt
2251799814165709      8 -rw-r--r--   1 kurom    197609       4160 Apr 30 13:17 government/Media/New_funding_sources.txt
2251799814165706      8 -rw-r--r--   1 kurom    197609       4266 Apr 30 13:17 government/Media/New_Online_Resources.txt
2251799814165705     12 -rw-r--r--   1 kurom    197609       8883 Apr 30 13:17 government/Media/NJ_Legal_Services.txt
2251799814165710      8 -rw-r--r--   1 kurom    197609       4297 Apr 30 13:17 government/Media/Nonprofit_Buys.txt
3377699721008437      4 -rw-r--r--   1 kurom    197609       4076 Apr 30 13:17 government/Media/not_accessible_to_disabled.txt
2251799814165713      8 -rw-r--r--   1 kurom    197609       4398 Apr 30 13:17 government/Media/Oregon_Poor.txt
2251799814165714      4 -rw-r--r--   1 kurom    197609       2674 Apr 30 13:17 government/Media/Owning_a_Piece.txt
2251799814165717      4 -rw-r--r--   1 kurom    197609       3026 Apr 30 13:17 government/Media/Paralegal_Honored.txt
2251799814165719      8 -rw-r--r--   1 kurom    197609       4350 Apr 30 13:17 government/Media/Philly_Lawyers.txt
2251799814165722      8 -rw-r--r--   1 kurom    197609       5212 Apr 30 13:17 government/Media/Politician_Practices.txt
2251799814165723      4 -rw-r--r--   1 kurom    197609       2219 Apr 30 13:17 government/Media/Poor_Lacking_Legal_Aid.txt
3096224744297695     12 -rw-r--r--   1 kurom    197609       8794 Apr 30 13:17 government/Media/Poverty_Lawyers.txt
3096224744297792     12 -rw-r--r--   1 kurom    197609       8553 Apr 30 13:17 government/Media/predatory_loans.txt
3377699721008352      4 -rw-r--r--   1 kurom    197609       4063 Apr 30 13:17 government/Media/Pro-bono_road_show.txt
3377699721008357      4 -rw-r--r--   1 kurom    197609       3839 Apr 30 13:17 government/Media/Program_Lodges.txt
3096224744297707      4 -rw-r--r--   1 kurom    197609       2824 Apr 30 13:17 government/Media/Providing_Legal_Aid.txt
3096224744297793      4 -rw-r--r--   1 kurom    197609       3561 Apr 30 13:17 government/Media/pro_bono_efforts.txt
3096224744297699      8 -rw-r--r--   1 kurom    197609       4143 Apr 30 13:17 government/Media/Pro_Bono_Services.txt
3096224744297708      8 -rw-r--r--   1 kurom    197609       5329 Apr 30 13:17 government/Media/Raising_the_Bar.txt
1688849860744431      4 -rw-r--r--   1 kurom    197609       4046 Apr 30 13:17 government/Media/Rental_rules.txt
3096224744297814      4 -rw-r--r--   1 kurom    197609       3039 Apr 30 13:17 government/Media/residents_sue_city.txt
1688849860744432      8 -rw-r--r--   1 kurom    197609       5333 Apr 30 13:17 government/Media/Retirement_Has_Its_Appeal.txt
3096224744297714      8 -rw-r--r--   1 kurom    197609       4166 Apr 30 13:17 government/Media/RoanokeTimes.txt
3377699721008371      4 -rw-r--r--   1 kurom    197609       3791 Apr 30 13:17 government/Media/Rumble_in_the_Bronx.txt
1688849860744439      4 -rw-r--r--   1 kurom    197609       1783 Apr 30 13:17 government/Media/Self-Help_Website.txt
1688849860744440      8 -rw-r--r--   1 kurom    197609       5287 Apr 30 13:17 government/Media/Service_Agency.txt
3096224744297723      4 -rw-r--r--   1 kurom    197609       3876 Apr 30 13:17 government/Media/State_funding.txt
3377699721008381      8 -rw-r--r--   1 kurom    197609       4659 Apr 30 13:17 government/Media/Supporting_Legal_Center.txt
1688849860744446     12 -rw-r--r--   1 kurom    197609       9277 Apr 30 13:17 government/Media/Survey.txt
1688849860744447      8 -rw-r--r--   1 kurom    197609       6125 Apr 30 13:17 government/Media/Targeting_Domestic_Violence.txt
1688849860744448     16 -rw-r--r--   1 kurom    197609      14486 Apr 30 13:17 government/Media/Terrorist_Attack.txt
1688849860744449      8 -rw-r--r--   1 kurom    197609       5397 Apr 30 13:17 government/Media/Texas_Lawyer.txt
1688849860744450      4 -rw-r--r--   1 kurom    197609       3776 Apr 30 13:17 government/Media/Texas_Supreme_Court.txt
1688849860744451      4 -rw-r--r--   1 kurom    197609       3209 Apr 30 13:17 government/Media/The_Bend_Bulletin.txt
1688849860744452      4 -rw-r--r--   1 kurom    197609       2757 Apr 30 13:17 government/Media/The_Columbian.txt
1688849860744453     12 -rw-r--r--   1 kurom    197609       8468 Apr 30 13:17 government/Media/The_State_of_Pro_Bono.txt
1688849860744454      8 -rw-r--r--   1 kurom    197609       5552 Apr 30 13:17 government/Media/Too_Crucial_to_Take_Cut.txt
1688849860744455      8 -rw-r--r--   1 kurom    197609       4226 Apr 30 13:17 government/Media/Towson_Attorney.txt
1688849860744456      8 -rw-r--r--   1 kurom    197609       5938 Apr 30 13:17 government/Media/Understanding.txt
1688849860744457      8 -rw-r--r--   1 kurom    197609       6577 Apr 30 13:17 government/Media/Unusual_Woodburn.txt
1688849860744458     12 -rw-r--r--   1 kurom    197609       8787 Apr 30 13:17 government/Media/Using_Tech_Tools.txt
1688849860744459      4 -rw-r--r--   1 kurom    197609       2299 Apr 30 13:17 government/Media/Valley_Needing_Legal_Services.txt
1688849860744460      8 -rw-r--r--   1 kurom    197609       4443 Apr 30 13:17 government/Media/Volunteers_Step_Up.txt
3096224744297815      4 -rw-r--r--   1 kurom    197609       3175 Apr 30 13:17 government/Media/water_fees.txt
1688849860744461      8 -rw-r--r--   1 kurom    197609       7070 Apr 30 13:17 government/Media/Weak_economy.txt
1688849860744462      4 -rw-r--r--   1 kurom    197609       2090 Apr 30 13:17 government/Media/Wilmington_lawyer.txt
1688849860744463      4 -rw-r--r--   1 kurom    197609       2609 Apr 30 13:17 government/Media/Wingates_winds.txt
1688849860744464      4 -rw-r--r--   1 kurom    197609       3914 Apr 30 13:17 government/Media/Workers_aid_center.txt
3377699721008403      8 -rw-r--r--   1 kurom    197609       5212 Apr 30 13:17 government/Media/Working_for_Free.txt
2533274790876516      4 drwxr-xr-x   1 kurom    197609          0 Apr 30 13:17 government/Post_Rate_Comm
2533274790876552     40 -rw-r--r--   1 kurom    197609      40707 Apr 30 13:17 government/Post_Rate_Comm/Cohenetal_comparison.txt
3096224744297829     24 -rw-r--r--   1 kurom    197609      21294 Apr 30 13:17 government/Post_Rate_Comm/Cohenetal_Cost_Function.txt
3096224744297842     44 -rw-r--r--   1 kurom    197609      43325 Apr 30 13:17 government/Post_Rate_Comm/Cohenetal_CreamSkimming.txt
3096224744297843     36 -rw-r--r--   1 kurom    197609      33313 Apr 30 13:17 government/Post_Rate_Comm/Cohenetal_DeliveryCost.txt
2533274790876544     36 -rw-r--r--   1 kurom    197609      34631 Apr 30 13:17 government/Post_Rate_Comm/Cohenetal_RuralDelivery.txt
3096224744297857     36 -rw-r--r--   1 kurom    197609      36622 Apr 30 13:17 government/Post_Rate_Comm/Cohenetal_Scale.txt
2533274790876554     24 -rw-r--r--   1 kurom    197609      23191 Apr 30 13:17 government/Post_Rate_Comm/Gleiman_EMASpeech.txt
1688849860744591     28 -rw-r--r--   1 kurom    197609      26743 Apr 30 13:17 government/Post_Rate_Comm/Gleiman_gca2000.txt
1688849860744592     76 -rw-r--r--   1 kurom    197609      77426 Apr 30 13:17 government/Post_Rate_Comm/Mitchell_6-17-Mit.txt
3096224744297877     48 -rw-r--r--   1 kurom    197609      46268 Apr 30 13:17 government/Post_Rate_Comm/Mitchell_RMVancouver.txt
2533274790876566     40 -rw-r--r--   1 kurom    197609      38655 Apr 30 13:17 government/Post_Rate_Comm/Mitchell_spyros-first-class.txt
3096224744297887     24 -rw-r--r--   1 kurom    197609      21547 Apr 30 13:17 government/Post_Rate_Comm/Redacted_Study.txt
3096224744297888     36 -rw-r--r--   1 kurom    197609      33322 Apr 30 13:17 government/Post_Rate_Comm/ReportToCongress2002WEB.txt
2533274790876585     12 -rw-r--r--   1 kurom    197609      11887 Apr 30 13:17 government/Post_Rate_Comm/WolakSpeech_usps.txt
```
* Finally, the `ls` option after `find` basically prints out the current path name alongside statistics including user, size and modification date. Although it is much wordier than the previous outputs, it could be helpful if one wanted to know what dates some files within the path were modified, alongside if they wanted to check how many hard links are within each file or child directory of said path.
