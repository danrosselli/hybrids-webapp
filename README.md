## Hybrids framework boilerplate

This boilerplate was created to serve as a basis for creating webapps. It has integrated some technologies that will facilitate development, such as Vite, Hybrids, Bootstrap and Capacitor.

Each one will serve a function: Vite for packaging the application, Hybrids is a reactive framework that facilitates the creation of web components, Bootstrap for grid UI and components and Capacitor to generate mobile version.


### Running this example

To run this boilerplate you need `node` installed. If you prefer to use `bun`, it will be much faster, so it is recommended!

To install dependencies `npm install` or `bun install`.
To run the provided example, you can use `npm start` or `bun start` command.

```bash
npm start
```

```bash
bun start
```

### Create a mobile application

To create a mobile application from this boilerplate, you first need to generate a build with `vite`, and then create the android project:

1. Generate the build:

```bash
bunx vite build
```

2. Add the android folder:

```bash
bunx cap add android
```

3. Open the project in Android Studio:

```bash
bunx cap open android
```

4. If there is a change in the build, just synchronize it with the android folder:

```bash
bunx cap sync
```

Now, you can execute this application in Android Studio, and send to mobile.
Capacitor can create applications for iOS as well, in which case you need to add an additional library for it. See Capacitor documentation for more details.
