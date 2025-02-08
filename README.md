# Abe App 0.1.0  
![Alt text](https://github.com/abeamar/abeApp/blob/main/logo.png) <br>
App created using Visual Studio, C#, WPF, T-SQL, WMI. This App is for Light DBA everyday work on monitoring and troubleshooting.
<hr>
 <p dir="auto">
        <a href="#about">1. About</a><br>
        <a href="#options">2. Options</a><br>
        <a href="#resource"> 2.1. System</a><br>
        <a href="#errors"> 2.2. Errors</a><br>
        <a href="#sessions"> 2.3. Sessions</a><br>
        <a href="#sessions"> 2.4. Locks</a><br>
        <a href="#conclusion">3. Conclusion</a><br>
    </p>
    <hr>
    <br>
     <section id="about">
        <h2>1. About</h2>
        <p>The primary focus of this project is to make an app that will give all the necessary help tools for database administrator in their everyday monitoring work. This app was made not just as a showcase but also as a fully functional tool. <br>I've also implemented in the app to run as a trial version, after 30 days the login button will stop working. <br>Below are the product screens. <br>The app is created for MS SQL.</p>
    </section>
        <br>

![Alt text](https://github.com/abeamar/abeApp/blob/main/abePreview2.png)
        <br>
            <hr>
    <section id="options">
        <h2>2. Options</h2>
        <p>The App is divided in few forms; System, Errors, Sessions, Locks. Each section gives multiple options to interact based on the topic name. On the first panel you have an option to log in using SQL user or using Windows credentials.</p>
    </section>
            <hr>
    <section id="resource">
        <h2>2.1. System</h2>
        <p>In this section you get all the important information about the SQL Instance (configuration, settings, behavior), network config, disk, cpu, ram info. On the sql panel you can see db relevant info (state, mode, sessions count)<br>From this section you can open panels that will give info about "Active Restore process" (in percentage), "Restore History" (with option to filter db), "Sizes of db files", "Sizes of tables in specific db", fragmentation.</p>
    </section>
            <hr>
    <section id="errors">
        <h2>2.2. Errors</h2>
        <p>In this section you can check and filter error logs on your SQL Instance. It contains both system and user-defined events information.</p>
    </section>
            <hr>
        <section id="sessions">
        <h2>2.3. Sessions</h2>
        <p>In this section you can check "Active Sessions" (with detail info about sessions behavior), list of all sessions with option to filter session state and target database of interest, option to check oldest active sessions.</p>
            <hr>
    </section>
        <section id="locks">
        <h2>2.4. Locks</h2>
        <p>In this section you can make events with option to create, purge and monitor preseted data. We are focusing on blocks, deadlocks, with specially created queries to have all the relavant info.<br>With debugEvent you can track specific object for troubleshooting scenarios.</p>
    </section>
            <br>
            <hr>
    <section id="conclusion">
        <h2>3. Conclusion</h2>
        <p>Overall, the purpose of the project was to challenge myself, to acquire skills and logic in making apps and also implement my knowledge and best practices in the MS SQL database field.<b> The end result is a fully functional and very useful tool to have in dba arsenal.</p>
    </section>
        <br>

