### Marasam Backend 

## How to setup the project on local machine

1. **Clone the Repository:**
   ```bash
   git clone <repository_url>
   ```

2. ** Composer install **
   ```bash
   composer install
   ```

3. **Running Laravel Sails:**
   - Navigate into the project directory and run:
     ```
     ./vendor/bin/sail up
     ```

4. **Running Migrations:**
   - If this is your first time running the application, run the following command to migrate the database:
     ```bash
     ./vendor/bin/sail migrate
     ```

5. **Setting Permissions (Linux Users):**
   - If you are using a Linux-based operating system, it's recommended to set the appropriate permissions for the storage directory by running:
     ```bash
     sudo chmod -R ugo+rw storage
     ```


## Notes
- If you need to run social login on your machine then please use ngrok to expose your local server to the internet.
- Ask for the `.env` file from the project owner to run the project on your local machine.
