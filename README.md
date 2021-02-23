# AWS-config-rules
Custom AWS config rules which can be deployed using RDK(Rule Development Kit).

## Development Setup

1. Clone the repository::
   ```
   https://github.com/manish97-ai/AWS-config-rules.git
   ```
2. Install dependencies::
   ```
   pip install -r requirements.txt
   ``` 
3. Setup AWS cli:
   ```
   aws configure
   * Enter following details:
       i.   AWS Access Key ID 
       ii.  AWS Secret Access Key 
       iii. Default region name
       iv.  Default output format (Optional)
   ```
4. Deploy rule::
   ```
   rdk deploy NAME_OF_THE_RULE
   ```

## For more information

1. RDK documentation- https://github.com/awslabs/aws-config-rdk
