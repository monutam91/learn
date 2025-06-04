## IaaS Compute

* There are pre-built images to choose from, which already has OS installed on themselves
* There's also a marketplace where vendors can provide their own images.
    - Some of these are Free, but some of them are including some addtional fees. Read the description carefully.
* Instance types:
    - t2, t3, ... -- these are instance families
    - t and m are the most commonly used general
    - t family, when used below thresholds, you earn creadity, which you can use at higher usages
    - m class instances are more expensive, but doN't use CPU credits, good for continous large CPU usage
    - For mor CPU intensive use c class
    - Memory optimized r and s classes for memory intensive tasks, or there are GPU optimized ones for tasks like AI training
    - AWS ahs a pricing calcualtor at calcualtor.aws
    - You can use it to estimate the costs of an EC2 instance
    - You have to setup key-pair for SSH
    - The AMI images do not always have the latest updates, so make sure to update
    - Rebooting instance keeps it on the same phisical server, while stopping and starting will move it to a different one
    - Auto-scaling: horizontal. Recommended AWS course on automation and optimization
    - Reserved instances: Planned on demand instances where you get a discount from the price by several different strategies
