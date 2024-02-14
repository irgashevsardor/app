1. Generate the `.htpasswd` file inside the project root directory using [apache2-utils](https://packages.debian.org/buster/apache2-utils).

   ```
   sudo htpasswd -c .htpasswd user1
   ```
2. Rename `.env.example` to `.env` and set your environment variables.
