> KU Java Project 2022

วิธีการติดตั้งหรือรันโปรแกรม
---------------
* ไปที่ Report-Desktop-Application\KUComplaint\
* Double click CS211-Project211-sunofthebeach-KUComplaint.jar เพื่อ run โปรแกรม

#
การวางโครงสร้างไฟล์
---------------
```
Report-Desktop-Application
|   .gitignore
|   pom.xml
|   README.md
|
+---data
|   |   admin.csv
|   |   allReport.csv
|   |   claiming.csv
|   |   inappropriateContentReport.csv
|   |   inappropritateUserReport.csv
|   |   officer.csv
|   |   register.csv
|   |
|   \---images
|       \---avatar
|              ...
|
+---KUComplaint
|   |   CS211-Project211-sunofthebeach-KUComplaint.jar
|   |   KU Complaint Application.pdf
|   |   project211-sunofthebeach-uml-controller.png
|   |   project211-sunofthebeach-uml-model.png
|   |   project211-sunofthebeach-uml-service.png
|   |
|   \---data
|       |   admin.csv
|       |   allReport.csv
|       |   claiming.csv
|       |   inappropriateContentReport.csv
|       |   inappropritateUserReport.csv
|       |   officer.csv
|       |   register.csv
|       |
|       \---images
|           \---avatar
|                  ...
|
\---src
   \---main
       +---java
       |   |   module-info.java
       |   |
       |   +---com
       |   |   \---github
       |   |       \---saacsos
       |   |               FXRouter.java
       |   |               
       |   \---ku
       |       \---cs
       |           |   Main.java
       |           |   ProjectApplication.java
       |           |
       |           +---controllers
       |           |   +---admin
       |           |   |      AdminAboutProgramController.java
       |           |   |      AdminHomeController.java
       |           |   |      AdminOrganizerController.java
       |           |   |      AdminProfileController.java
       |           |   |      BannedUserListController.java
       |           |   |      ClaimingListController.java
       |           |   |      CreateOfficerController.java
       |           |   |      InappropriateContentReportListController.java
       |           |   |      InappropriateContentReportListDetailController.java
       |           |   |      InappropriateController.java
       |           |   |      InappropriateUserReportListController.java
       |           |   |      InappropriateUserReportListDetailController.java
       |           |   |      NisitDetailController.java
       |           |   |      OfficerDetailController.java
       |           |   |
       |           |   +---main
       |           |   |      AboutProgramController.java
       |           |   |      ClaimingController.java
       |           |   |      HomeController.java
       |           |   |      LoadingController.java
       |           |   |      OrganizerController.java
       |           |   |      RegisterController.java
       |           |   |
       |           |   +---nisit
       |           |   |      NisitAboutProgramController.java
       |           |   |      NisitHomeController.java
       |           |   |      NisitOrganizerController.java
       |           |   |      NisitProfileController.java
       |           |   |      NisitReportController.java
       |           |   |      NisitReportInappropriateContentController.java
       |           |   |      NisitReportInappropriateUserController.java
       |           |   |      NisitReportListController.java
       |           |   |      NisitReportListDetailController.java
       |           |   |
       |           |   \---officer
       |           |          OfficerAboutProgramController.java
       |           |          OfficerFixReportController.java
       |           |          OfficerHomeController.java
       |           |          OfficerOrganizerController.java
       |           |          OfficerProfileController.java
       |           |          OfficerReportDetailController.java
       |           |
       |           +---models
       |           |   +---account
       |           |   |      Admin.java
       |           |   |      AdminList.java
       |           |   |      Nisit.java
       |           |   |      NisitList.java
       |           |   |      Officer.java
       |           |   |      OfficerList.java
       |           |   |      User.java
       |           |   |      UserList.java
       |           |   |
       |           |   \---report
       |           |          Claiming.java
       |           |          ClaimingList.java
       |           |          InappropriateReport.java
       |           |          InappropriateReportList.java
       |           |          Report.java
       |           |          ReportList.java
       |           |
       |           \---services
       |                   AdminListDataSource.java
       |                   ClaimingListDataSource.java
       |                   DataSource.java
       |                   Filterer.java
       |                   InappropriateReportListDataSource.java
       |                   Information.java
       |                   NisitListDataSource.java
       |                   OfficerListDataSource.java
       |                   ReportListDataSource.java
       |                   ThemeMode.java
       |          
       \---resources
            \---ku
                \---cs
                    |   aboutProgram.fxml
                    |   adminAboutProgram.fxml
                    |   adminHome.fxml
                    |   adminOrganizer.fxml
                    |   adminProfile.fxml
                    |   bannedUserList.fxml
                    |   claiming.fxml
                    |   claimingList.fxml
                    |   claimingListDetail.fxml
                    |   createOfficerAccount.fxml
                    |   home.fxml
                    |   inappropriate.fxml
                    |   inappropriateContentReportList.fxml
                    |   inappropriateContentReportListDetail.fxml
                    |   inappropriateUserReportList.fxml
                    |   inappropriateUserReportListDetail.fxml
                    |   loading.fxml
                    |   nisitAboutProgram.fxml
                    |   nisitDetail.fxml
                    |   nisitHome.fxml
                    |   nisitOrganizer.fxml
                    |   nisitProfile.fxml
                    |   nisitReport.fxml
                    |   nisitReportInappropriateContent.fxml
                    |   nisitReportInappropriateUser.fxml
                    |   nisitReportList.fxml
                    |   nisitReportListDetail.fxml
                    |   officerAboutProgram.fxml
                    |   officerDetail.fxml
                    |   officerFixReport.fxml
                    |   officerHome.fxml
                    |   officerOrganizer.fxml
                    |   officerProfile.fxml
                    |   officerReportDetail.fxml
                    |   organizer.fxml
                    |   register.fxml
                    |
                    +---forButton
                    |      dark.css
                    |      light.css
                    |      pom.xml
                    |      Prompt-Regular.tff
                    |
                    \---images
                        |   back.png
                        |   BgClaimTheir_Rights.png
                        |   claiming.png
                        |   ClaimList.png
                        |   ComplaintsHandling.png
                        |   contact.png
                        |   Content_inappropriateness.png
                        |   Content_inappropriateness_detail.png
                        |   createOfficerAccount.png
                        |   danger.png
                        |   EveryLayerTop.png
                        |   FixReport.png
                        |   follower.png
                        |   homePage.gif
                        |   Howto.png
                        |   icon_Admin.png
                        |   icon_Block.png
                        |   icon_Change.png
                        |   icon_List.png
                        |   icon_Organizer.png
                        |   icon_Tutalrial.png
                        |   imagehome.jpg
                        |   InappropriateReports.png
                        |   InappropriateUserList.png
                        |   login.png
                        |   logo.gif
                        |   LOGO.png
                        |   Main.png
                        |   Manage.png
                        |   ManageReport.png
                        |   Nisit_Complaint.png
                        |   Nisit_Detail.png
                        |   Nisit_Layer.png
                        |   Nisit_Layer2.png
                        |   Nisit_logoutComplaint.png
                        |   Nisit_Profile.png
                        |   Nisit_storyComplaint.png
                        |   Nisit_writeComplaint.png
                        |   Nisit_writeComplain2.png
                        |   Nisit_writeComplaintPost.png
                        |   Officer_Detail.png
                        |   Officer_ListUser.png
                        |   Officer_report.png
                        |   Officer_report1.png
                        |   OfficerOrganization.png
                        |   OfficerReportDetail.png
                        |   owl.png
                        |   password.png
                        |   passwordNisit.png
                        |   passwordOfficerChange.png
                        |   photo-camera.png
                        |   profile.png
                        |   profileAdmin.png
                        |   profileOfficer.png
                        |   ReadTheReport.png
                        |   Report_inappropriateness.png
                        |   ReportContentList.png
                        |   ReportUserList.png
                        |   road-barrier.png
                        |   search.png
                        |   siren.png
                        |   stop.png
                        |   submit.png
                        |   TopicOrganizer.png
                        |   tutorial01.png
                        |   tutorial0201.png
                        |   tutorial0202.png
                        |   tutorial0203.png
                        |   tutorial0301.png
                        |   tutorial0302.png
                        |   tutorial0401.png
                        |   tutorial0402.png
                        |   unfriend.png
                        |   User_inappropriateness.png
                        |   User_inappropriateness_Datail.png
                        |   username.png
                        |   white-login.png
                        |   white-password.png
                        |   white-username.png
                        |   worm.png
                        |   WriteTheReport.png
                        |
                        +---organizer
                        |      Meimay.jpg
                        |      Meimay2.png
                        |      organizer Meimay.png
                        |      organizer Ping.png
                        |      organizer Prim.png
                        |      organizer ta.png
                        |      Ping.jpg
                        |      Ping2.png
                        |      Prim.jpg
                        |      Prim2.png
                        |      Ta.jpg
                        |      Ta2.png
                        |
                        \---staff
                               header.png
                               topic.png
                               topic1.png
```

#
ตัวอย่างข้อมูลผู้ใช้ระบบ
---------------
```
Admin
username : pingph25251
password : 6410401124
```
```
Officer
username : bell123
password : 123
```
```
Nisit
username : ta123
password : 1234
```
```
Nisit
username : ping123
password : 123
```