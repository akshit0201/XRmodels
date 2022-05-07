# WebXR Models

![image](src/client/images/ss.png)
## About
This repo contains three WebXR models: [earth](src/client/earth.ts) (VR version), [earth](src/client/ar.ts) (AR version) & a pre-downloaded [model](src/client/ar-model.ts) in AR.

The models can be toggled by uncommenting the desired file in [index.html](dist/client/index.html).
## Installing

You can run this repo by clicking green code button and choosing "open with CodeSpaces" from the dropdown. With CodeSpaces, you can run Visual Studio Code on your browser and code from anywhere. [Sign up for CodeSpaces Beta](https://github.com/features/codespaces?WT.mc_id=aiml-8567-ayyonet) and see the video for details.

[![How to set up remote development with Github Code Spaces and VS Code](http://img.youtube.com/vi/ZWJglERhXLw/0.jpg)](https://youtu.be/ZWJglERhXLw)

If you want to setup your own local environment follow the steps here:

1. Clone Repository

```bash
git clone https://github.com/akshit0201/XRmodels.git
```

2. CD into folder
```bash
cd XRmodels
```

3. Install TypeScript

```bash
npm install -g typescript
```

4. Install dependencies

```bash
npm install
```

5. Start it

```bash
npm run dev
```

6. Visit [http://127.0.0.1:3000/](http://127.0.0.1:3000/)


7. Edit project
```bash
code .
```

8. To get an HTTPS connection, run
```bash
npm install ngrok
ngrok http 3000
```

9. Check the `Forwarding ... https:` line and visit the link
