# Custom Nx Workspace ESLint Rules

## Setup

Run `npm install`

## Rules Cannot Be Found Without Nx Console Extension Being Installed

These rules cannot be found by the eslint VS Code extension without the Nx Console extension being installed.

If you go to `apps/example/src/app/app.component.ts:1` without the extension installed you will see an error saying:
`Definition for rule '@nrwl/nx/workspace/my-custom-rule' was not found.eslint(@nrwl/nx/workspace/my-custom-rule)`

If you install the Nx Console and then restart the ESLint Server for VS Code it will be able to find the rule.
