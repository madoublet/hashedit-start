# Hashedit Start

Hashedit Start is the starter site for a Hashedit powered site.  Hashedit Start is powered by Static Spark.  Hashedit Start requires Node JS, NPM, and Bower.

## Getting Started

##### 1. Create a directory for your NodeJS site.
```
mkdir staticspark
cd static-spark
```

##### 2. Clone the repository into your folder structure.
```
git clone https://github.com/madoublet/static-spark .
```

##### 3. Copy the configuration file.  Update the app.url, google.clientId, google.clientSecret, and add an authorized email address.

```
cp config.sample.js config.js
nano config.js
```

##### 4. Create the public directory.
```
mkdir public
```

##### 5. Install dependencies
```
npm install
```

##### 6. Clone the starter site.
```
cd public
git clone https://github.com/madoublet/hashedit-start .
```

##### 7. Run bower
```
bower update
```

##### 8. Start your server
```
cd ..
DEBUG=static-spark npm start
```