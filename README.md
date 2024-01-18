# AWS secrets manager demo code

## Configuration

To enable AWS SDK to find the necessary credentials, follow these steps:

1. Create a `.aws` directory in the root of your server if it doesn't exist.
2. Inside the `.aws` directory, create a `credentials` file.
3. Open the `credentials` file and add your AWS credentials in the following format:

   ```plaintext
   [default]
   aws_access_key_id=jbdjgflkfnkljdngkjdfnglkzdf
   aws_secret_access_key=kdfbkdzfjfbgjgljbdfljghbfjjsJHFSBLHJ
   ```

   Replace `aws_access_key_id` & `aws_secret_access_key` with your actual AWS access key and secret key respectively.

4. Save and close the `credentials` file.

Now, your AWS SDK should be able to find the credentials when needed.
