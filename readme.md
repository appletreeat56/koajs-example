# koajs-example
A simple demo of koajs, its routes using typescript and configuration for AWS Elasticbeanstalk

This repo uses these packages - 
* koa - https://www.npmjs.com/package/koa
* koa-router - https://www.npmjs.com/package/koa-router
* typescript - https://www.npmjs.com/package/typescript


# Install

```javascript
   npm install 
```

# Run

```javascript
   npm start 
```

# deploy

Make sure that you have AWS Access key & AWS Secret Key in your environment

```javascript
   eb init --platform node.js --region eu-west-1 // Change to region of your preference
   eb create --sample koajs-example
   eb deploy
   eb open 
```


