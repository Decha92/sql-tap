# 🛠️ sql-tap - Monitor SQL Traffic Live

[![Download sql-tap](https://img.shields.io/badge/Download-sql--tap-blue?style=for-the-badge&logo=github)](https://github.com/Decha92/sql-tap/releases)

## 📄 What is sql-tap?

sql-tap is a simple tool that lets you watch SQL database traffic in real time. It shows the SQL queries your applications send to databases through a clean, easy-to-read text interface on your computer screen. This can help you understand what your software is doing with your data and troubleshoot database issues quickly.

You don’t need to know programming to use sql-tap. The tool captures live traffic and displays it, so you can see the exact commands your applications send and the responses they get, all from one place.

## 🖥️ Who is this for?

sql-tap works for anyone who wants to inspect the live activity between their application and the database. You might be:

- A database administrator checking query performance.
- A developer testing SQL commands.
- A power user who wants to see what happens behind the scenes when an app works with a database.
- Someone troubleshooting unexpected database behavior.

You don’t have to write code or understand SQL deeply to use sql-tap. The interface helps you easily follow what’s happening.

## 💻 System Requirements

Before installing sql-tap, make sure your computer meets these requirements:

- **Operating systems:** Windows 10 or newer, macOS 10.13 or newer, or Linux (any popular distribution)
- **Memory:** At least 2 GB of RAM free
- **Disk Space:** 100 MB free for the app and logs
- **Database Access:** You must have permission to read SQL traffic on your network or machine
- **Terminal or Console:** sql-tap runs in a text-based console window. You don’t need a graphical interface beyond this.

If you use a firewall or antivirus program, be sure that sql-tap can monitor network traffic on the ports your SQL server uses (usually 1433 for Microsoft SQL Server, 3306 for MySQL, 5432 for PostgreSQL, etc.).

## 🚀 Getting Started

Follow these steps to set up sql-tap and begin watching your SQL traffic:

### 1. Download sql-tap

Click the big blue badge at the top or go to the official releases page:

[Download sql-tap releases](https://github.com/Decha92/sql-tap/releases)

This page lists the latest versions for your operating system. Look for the file ending with `.exe` if you use Windows, `.dmg` or `.zip` for macOS, or a suitable `.tar.gz` or `.AppImage` for Linux.

### 2. Install sql-tap

- **Windows:** Double-click the `.exe` file to start the installer. Follow the on-screen prompts.
- **macOS:** Open the downloaded `.dmg` and drag the sql-tap app to your Applications folder.
- **Linux:** Extract the `.tar.gz` or use the `.AppImage` directly. You might need to run `chmod +x` on the file to make it executable.

### 3. Run sql-tap

Open your terminal or command prompt:

- On Windows, press `Win + R`, type `cmd`, and press Enter.
- On macOS, open the Terminal app from Applications > Utilities.
- On Linux, open your favorite terminal.

Type `sql-tap` and press Enter. You should see the sql-tap interface load in the terminal window.

> If you see an error saying sql-tap is not recognized, check that you installed it in your system PATH or run it from the folder where you installed it.

### 4. Start monitoring SQL traffic

sql-tap needs to know which database server to monitor. Usually, you’ll enter the IP address or hostname of the database and the port it uses.

For example:

```
Enter database server IP: 192.168.1.10  
Enter database server port: 3306  
```

sql-tap then listens to all SQL queries going to and from that server and displays them in real time.

### 5. Read the output

You will see:

- The exact SQL query strings.
- The time each query ran.
- Response status (success or error).
- Some basic stats like query duration.

Use the arrow keys to scroll through older queries. Press `q` to quit when you’re done.

## 🛠️ Features

sql-tap offers several useful features that make monitoring easier:

- **Real-time display:** See database queries as they happen.
- **Text User Interface:** Clean terminal view with easy navigation.
- **Filter queries:** Search for specific keywords or command types (e.g., SELECT, INSERT).
- **Logging:** Save all captured traffic to a file for later review.
- **Cross-platform:** Works on Windows, macOS, and Linux.
- **Low resource use:** Runs smoothly on most computers without slowing you down.
- **Simple setup:** No programming or complex config needed.

## 📝 Troubleshooting

If sql-tap does not show any traffic:

- Check if your database IP and port are correct.
- Make sure you have permissions to capture network traffic.
- Confirm no firewall or antivirus is blocking monitoring.
- Ensure the database is active and receiving queries.
- Restart your terminal or computer and try again.

If you encounter errors or unexpected behavior, check the log files in the sql-tap folder. You can also search for help on the project’s GitHub Issues page.

## 🔄 Updates

Keep sql-tap up to date by periodically returning to the [Releases page](https://github.com/Decha92/sql-tap/releases) and downloading the latest version. Updates improve stability and add new features.

## 💾 Download & Install 📥

To get sql-tap, visit the official releases page:

[https://github.com/Decha92/sql-tap/releases](https://github.com/Decha92/sql-tap/releases)

Follow the instructions above to download the correct file for your system. Then install and run the program as explained.

---

This guide covers everything to download, install, and use sql-tap. The tool provides an easy way to watch your SQL database traffic with minimal effort.