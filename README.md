# AbeMon App 1.0.0  
[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Callibril&lines=SQL+Tool+for+Troubleshooting+your+env;Monitor+and+Debug+using+this+Tool..)](https://git.io/typing-svg)<br>
App created using Visual Studio, C#, WinForms, T-SQL, PowerShell, WMI. This App is for Light DBA everyday work on monitoring and troubleshooting on MSSQL.
<hr>
 <p dir="auto">
        <a href="#about">1. About</a><br>
        <a href="#options">2. Options</a><br>
        <a href="#resource"> 2.1. System</a><br>
        <a href="#errors"> 2.2. Errors</a><br>
        <a href="#sessions"> 2.3. Sessions</a><br>
        <a href="#locks"> 2.4. Locks</a><br>
        <a href="#export"> 2.5. Export</a><br>
        <a href="#debug"> 2.6. Debug</a><br>
        <a href="#conclusion">3. Conclusion</a><br>
    </p>
    <hr>
    <br>
     <section id="about">
        <h2>1. About</h2>
        <p>The primary focus of this project is to make an App that will have all the necessary tools for database administrator in their everyday monitoring work. This app is a fully functional tool. <br>The app is provided as a trial for 30 days, allowing you to experience its full functionality. Feel free to contact me if you like what you see. This App is designed to deliver smooth performance while using minimal system resources, consuming just 10-20MB of RAM.<br>Full Article on dev.to<br>
         <a href="https://dev.to/abeamar/abemon-ms-sql-tool-v100-monitor-and-debug-60m"><img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/2mwf43v0fxe7f3z8m67y.jpg" height="270" width=540 /></a> 
         <br> <h1>🐔 AbeMon Install options: </h1><br>
         <pre><code>git clone "https://github.com/abeamar/AbeMon.git"</code></pre><br>
        Choose the installation method that works best for you!<br>

<ol>
  <li>Using the .exe or .msi Installer:<br>https://github.com/abeamar/AbeMon/main/AbeSetup.msi <br>https://github.com/abeamar/AbeMon/main/setup.exe</p></li>
  <li>Manual Installation (Copying the Folder abeSetup)<br>After copying, you can run the application directly from that folder.</li>
</ol>
              <br>
              <br>Below are some of the product screens. <br>
        Demo: App work preview of version v 0.1.6:
        <a href="https://vimeo.com/manage/videos/1124492178" target="_blank">Video link on Vimeo</a>
    </section>
        <br>
            <hr>
    <section id="options">
        <h2>2. Options</h2>
        <p>The App is divided in few forms; System, Errors, Sessions, Locks, Export, Debug. Each section gives multiple options to interact based on the topic name. On the first panel you have an option to log in using SQL user or using Windows credentials.</p>
    </section>
            <hr>
    <section id="resource">
        <h2>2.1. System</h2>
        <p>In this section you get all the important information about the SQL Instance (configuration, settings, behavior), network config, disk, cpu, ram info. On the sql panel you can see db relevant info (state, mode, sessions count)<br>From this section you can open panels that will give info about "Active Restore process" (in percentage), "Restore History" (with option to filter db), "Sizes of db files", "Sizes of tables in specific db", fragmentation, and tempdb debuging</p>
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
        <p>In this section you can make events with option to create, purge and monitor preseted data. We are focusing on blocks, deadlocks, with specially created queries to have all the relavant info.<br>Block and Deadlock events are based on my sql script here (except now we store data in ring buffer, behaving as a client side select)  https://github.com/abeamar/sqlLockEvents <br>With debugEvent option you can track specific objects name for troubleshooting scenarios (error report).</p>
    </section>
            <br>
            <hr>
    <section id="export">
        <h2>2.5. Export</h2>
        <p>I created a PowerShell script that exports all SQL Server database objects along with their permissions into separate .sql files, organized into subfolders by object type (tables, views, procedures, functions).</p>
    </section>
            <br>
            <hr>
    <section id="debug">
        <h2>2.6. Debug</h2>
        <p>Tracking and analyzing older active sessions, failed jobs, failed replications, performing column capacity checks and more...</p>
    </section>
            <br>
            <hr>
    <section id="conclusion">
        <h2>3. Conclusion</h2>
        <p>Overall, the purpose of the project was to challenge myself, to acquire skills and logic in making apps and also implement my knowledge and best practices in the MS SQL database field.<b> The end result is a fully functional and very useful tool to have in dba arsenal.</p>
    </section>
        <br>

