## License Summary

This sample code is made available under a modified MIT license. See the LICENSE file.

## Reference Architecture: Multi Region Deployment using AWS CodePipeline

This reference architecture demonstrates how to use a single [AWS CodePipeline](https://aws.amazon.com/codepipeline/) in
one of your primary regions to deploy application to multiple secondary regions to improve both latency and availability
of your application. This orchestration of code movement from code checkin to deployment is securely handled 
by [AWS CodePipeline](https://aws.amazon.com/codepipeline/).

## Deployment Architecture
![](https://github.com/aws-samples/aws-codepipeline-cross-region-continuous-deployment/blob/master/images/multiregion-codepipeline.jpg)