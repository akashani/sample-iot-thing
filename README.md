A Really simple IoT "thing" for connecting to AWS IoT.

1. Get an IoT certificate & key from AWS IoT Core and place them in this directory, named `cert.pem` and `private.pem`.

2. Run `npm install` to download dependencies

3. Run this simulator with:

    npm start HOST STAGE CLIENTID
    
Where HOST is the MQTT endpoint for an AWS account, STAGE is the name of an environment (dev, prod, etc), and CLIENTID is a unique identifier for this "thing".

4. See messages published to the IoT topic `iotsample/STAGE/CLIENTID/data` in the AWS IoT Core Console.

Need help with your IoT project? Check out IoTanium @ http://www.onica.com/iotanium
