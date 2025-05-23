# Next Steps

Congratulations on generating your template!

## Completing your template

The next steps to complete the template are:

  1. Complete the fields in the `template.json` file.
     - It is really important to ensure `helpurl` is valid as this is where users of the template will be directed for help.
  2. Update `README.md`.
  3. Edit `wails.json` and ensure all fields are correct, especially:
     - `wailsjsdir` - path to generate wailsjs modules
     - `frontend:install` - The command to install your frontend dependencies
     - `frontend:build` - The command to build your frontend
  4. Remove any `public` or `dist` directories.
  5. Delete this file.

## Testing your template

You can test your template by running this command:

`wails init -n test -t F:\dev\wails\wails-vite-svelte-tailwind-template\svelte5`

### Checklist

Once generated, do the following tests:
  - Change into the new project directory and run `wails build`. A working binary should be generated in the `build/bin` project directory.
  - Run `wails dev`. This will compile your app and run it.
    - You should be able to see your application running on http://localhost:34115/

## Publishing your template

You can publish a template to a git repository and use it as follows:

`wails init -name test -t https://your/git/url`

EG: 

`wails init -name test -t https://github.com/leaanthony/testtemplate`

