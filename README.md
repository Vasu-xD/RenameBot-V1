# **Rename Bot with Thumbnails Support - V1**

🚀 **Super Fast Bot to Rename Files and Update Thumbnails in a Flash!**  
Whether you need to quickly rename your files or update the thumbnails, this bot is here to help you do it seamlessly and swiftly. Perfect for managing your media files and keeping things organized with just a few clicks!

---

## **Key Features:**
- **Instant File Renaming:** Rename any file in no time—just send the file and the new name!
- **Thumbnail Management:** Easily add, view, or delete thumbnails associated with your files.
- **Simple & Easy-to-Use Interface:** Interact with the bot using simple commands for a smooth user experience.

---

# 1. Deploy Locally

- To run the bot on your local machine or a VPS, follow these steps:

## Prerequisites

- Python 3.10 or higher installed.

- A Telegram bot token (get it via @BotFather).

- API ID and API HASH from my.telegram.org.

- Admin Telegram User IDs (separated by commas).


## Steps

1. Clone the Repository

```
git clone https://github.com/VasuXD/RenameBot-V1.git
cd RenameBot-V1
```


2. Install Dependencies Use pip to install the required libraries:

```
pip install -r requirements.txt
```


3. Set Up Environment Variables Rename the `example.env` file to `.env`:

```
mv example.env .env
```

Edit the .env file and replace placeholders with your details:

```
API_ID=123
API_HASH=abcdefghijklmnopqrstuvwxyz
BOT_TOKEN=1234567890:abcdergghijklmnopqrstuvwxyz
ADMIN=12345,09876
CAPTION=Your optional caption here
```


4. Run the Bot Start the bot using the following command:

```
python3 bot.py
```

---

# 2. Deploy Using GitHub Workflows

You can automate the deployment process using GitHub Actions.

Steps

1. Fork the Repository Fork this repository to your own GitHub account.


2. Add Secrets Go to the Settings > Secrets and variables > Actions section of your forked repository. Add the following secrets:

```
API_ID: Your unique API ID.

API_HASH: Your API hash.

BOT_TOKEN: The token for your bot.

ADMIN: The list of admin user IDs (separated by commas).

CAPTION: Optional caption for renamed files.
```


3. Edit the Workflow Ensure the `.github/workflows/deploy.yml` file is properly configured. Update as necessary for your hosting platform (e.g., Heroku, VPS).


4. Push Changes Any push to the main branch will trigger the workflow to deploy the bot.

---


## **Commands:**
- `/start` - Get started and see how the bot works!
- `/rename` - Reply with a file to rename and give it a new name!
- `/del` - Delete the current thumbnail attached to your file.
- `/view` - View the thumbnail currently associated with your file.

---

## **Important Announcement - V2 Coming Soon!**
🚨 **Note:** This is **`Version 1`** of the bot created in 2022, which uses `pyrogram` for handling the interactions. However, since `pyrogram` hasn't been updated from a year, we will soon release **`Version 2`** with **`Telethon support`** to improve performance and stability. Stay tuned for even better functionality and more features!

---

## **Credits:**
- **[Vasu](https://github.com/Vasu-xD)** for providing the amazing source code!
- Special thanks to **[Dan](https://github.com/delivrance)** for the awesome [pyrogram](https://github.com/pyrogram/pyrogram) library, which powers this bot!
- I am forgetting to mention the person who initially created a basic repository, and I do not have access to it. Therefore, the basic source code is derived from their work. Thank you!

---

## **Contact & Support:**
- Reach out to me for any questions or support via [Telegram](https://t.me/VasuXD).  
- If you need assistance or have suggestions, feel free to contact my bot: [@vasurobot](https://t.me/vasurobot).

---

## **Source Code & Updates:**
- Check out the source code on [GitHub - RenameBot-V1](https://github.com/VasuXD/RenameBot-V1) and follow along as we prepare for the exciting V2 release!

---

Stay tuned for more updates and improvements as we continue to enhance your experience!
