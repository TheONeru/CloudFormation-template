# CloudFormation-template
AWS CloudFormation-template
<p>依存関係解消のために以下の手順を踏まないと全て綺麗に作成できない</p>

<p>上のリソースが作成されていないと下のリソースはエラーが出るはず</p>

<p>VPC:</p>
<p>　-　DB:</p>
<p>　-　EC2:</p>
<p>　-　NAT:</p>
<p>　-　Endpoint:</p>

<p></p>

<p>DB,NAT:</p>
<p>　-　Fargate:</p>
<p>　　-　S3:</p>
<p>　　　-　CloudFront:</p>
