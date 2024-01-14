# 🌌 ASP.NET - Identity, Customization Login form
Below I present a more detailed instruction that will help users customize the login and registration form on their ASP.NET MVC website using the Identity library.

<div>
<img width="400" height="300" src="https://raw.githubusercontent.com/iuno-san/ASP.NET-IdentityCustom/main/img/Step_0.png" />
<img width="400" height="300" src="https://raw.githubusercontent.com/iuno-san/ASP.NET-IdentityCustom/main/img/Step_10.png" />
</div>
<br><br>

# ⚡️ Steps to customize the login form

#### 1. Open Visual Studio and load your existing project or create a new MVC project. <br><br> <img width="450" height="300" src="https://raw.githubusercontent.com/iuno-san/ASP.NET-IdentityCustom/main/img/Step_1.png" /> <br><br>

#### 2. Right-click on the main part of your MVC project (e.g. on the project name in the Solution Explorer pane). 

#### 3. Select "Add" and then "New Scaffolded Item". <br><br> <img width="450" height="300" src="https://raw.githubusercontent.com/iuno-san/ASP.NET-IdentityCustom/main/img/Step_2.png" /> <br><br>

#### 4. In the dialog box, select the "Identity" section on the left side.

#### 5. Click the "Add" button. <br><br> <img width="450" height="300" src="https://github.com/iuno-san/ASP.NET-IdentityCustom/blob/main/img/Step_3.png" /> <br><br> 

#### 6. Now all available files will appear, which you can download to your project and change from the Identity package. We are looking for "Account/Login" and "Account/Register" files, so select the corresponding options. <br><br> <img width="450" height="300" src="https://github.com/iuno-san/ASP.NET-IdentityCustom/blob/main/img/Step_5.png" /> <br><br> 

#### 7. Next, you will be asked to select the DbContext class file. If you don't have one, you can create one by clicking on the "Add" button and giving it an optimal name, such as "ApplicationDbContext." You can also select an existing DbContext class. <br><br> <img width="450" height="300" src="https://github.com/iuno-san/ASP.NET-IdentityCustom/blob/main/img/Step_4.png" /> <br><br> 

#### 8. After selecting the DbContext class, click the "Add" button. This will create "Areas/Identity/Data" and "Areas/Identity/Pages/Account" folders in your project, and the "Account" folder will contain the login and registration form files and others related to the Identity library.

#### 9. Now you can access the "Login.cshtml" file located in the "Areas/Identity/Pages/Account" folder and change it according to your preferences. <br><br> <img width="450" height="300" src="https://github.com/iuno-san/ASP.NET-IdentityCustom/blob/main/img/Step_6.png" /> <br><br>

#### 10. To display the login and registration sections on your page, go to the "_Layout.cshtml" file in the "Views/Shared" folder. Add the following code to import the partial content <code><_LoginPartial): &lt;partial name=&quot;_LoginPartial&quot;/&gt;</code> <br><br> <img width="450" height="300" src="https://github.com/iuno-san/ASP.NET-IdentityCustom/blob/main/img/Step_7.png" /> <br><br>

#### 11. In the "Program.cs" file, add the following line of code to enable Razor Pages support: <code>app.MapRazorPages();</code> <br><br> <img width="450" height="300" src="https://github.com/iuno-san/ASP.NET-IdentityCustom/blob/main/img/Step_8.png" /> <br><br>
<br>

# 😎 After completing these steps
the login and registration form modifications should be ready to be displayed on your website. Now you can enjoy the modifications and adapt them to your needs.

Have fun working on your project!

<img src="https://raw.githubusercontent.com/iuno-san/ASP.NET-IdentityCustom/main/img/Step_10.png" />
