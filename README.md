# Getting Started with p5-react-template

1. Create a new project by using this template by clicking [here](https://github.com/RobertMcReed/p5-react-template/generate)
2. Install dependencies with `yarn install`
3. Start the app with `yarn start`. You will see a demo animation.
4. Run `yarn create-animation` to create your own animation. This will create a file `./src/controller/animations/MyAnimation.ts`.
5. Rename `MyAnimation.ts` to something else and edit the class to create your own animation.
6. Export your `hotCanvas` and `Canvas` from your desired animation in `./src/controller/animations/index.ts` to see it in the browser.
7. Make as many animations as you want!

## Merging Updates

If there are changes to the template that you wish to pull in you can do so as follows:

1. Run `yarn add-remote` to add the template remote to git (only needs to be run once)
2. Run `yarn merge-remote` to pull in all updates from the remote. This will likely require you to fix merge conflicts.
