# Deploy NestJS on Seenode in seconds

This is a repo for deploying a minimal but production-ready NestJS application for deployment on [Seenode](https://seenode.com).

This example demonstrates how to deploy a simple NestJS app.

### Deploy in minutes
View our [guide on deploying NestJS apps](https://seenode.com/docs/services/web-services/framework-guides/javascript/nestjs/) on [seenode](https://seenode.com) in seconds.


## How to Deploy on Seenode

1.  **Connect Your Repository**: Go to the [Seenode dashboard](https://cloud.seenode.com), select **New Web Service**, and choose this Git repository.
2.  **Confirm Settings**: Seenode will detect the Node.js environment and suggest the correct commands.
    *   **Build Command**: `npm run build`
    *   **Start Command**: `npm run start:prod`
3.  **Deploy**: Click **Create Web Service**.

That's it! Your NestJS app will be deployed and available at a public URL.

### Key Features on Seenode

*   **Production-Ready**: By using the production start command, you are running an optimized build of your application.
*   **Automatic Port Handling**: Seenode manages port assignments by injecting the `$PORT` environment variable, which NestJS uses automatically.
*   **Seamless Scaling**: Scale your service horizontally or vertically with a few clicks from the Seenode dashboard as your traffic grows.
