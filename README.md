# What?

This is a wallet connect push server you can deploy as a firebase function.

# Setup

#### Step 0

Install firebase-tools (only needed if not yet installed).

```
npm install -g firebase-tools
```

#### Step 1

```
firebase init
```

Then select Javascript with NO Eslint and install dependencies with npm

#### Step 2

`firebase use --add`

Then select the project that contains the app that should receive the push notifications.

#### Step 3

```
cd functions
npm install
cd ..
```

# Deployment

`./gradlew deploy`

# License

MIT
