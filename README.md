# Resolving-npx-Installation-Issue-on-Windows


If you encounter the `EEXIST: file already exists` error when installing `npx`, follow these steps:

#### Option 1: Delete the Existing File Manually

1. Navigate to `C:\Users\KIIT(Main User file)\AppData\Roaming\npm\` using File Explorer.
2. Delete the `npx` file.
3. Run the installation command again:
    ```bash
    npm install -g npx
    ```

#### Option 2: Use the `--force` Option

1. Run:
    ```bash
    npm install -g npx --force
    ```

### Creating a New React App

After resolving the `npx` issue, create your React app with the following command:
```bash
npx create-react-app algotrading
```

---

This should help you or anyone else encountering the same issue.
