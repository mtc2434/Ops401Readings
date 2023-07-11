# Compute Abstractions on AWS: A Visual Story
# Explain the levels of abstraction in AWS to someone without a technical background.
- Infrastructure Layer: This is the foundational layer where physical servers, networks, and storage exist.
-  Compute Layer: This layer abstracts away the underlying infrastructure and provides virtual servers or instances.
-  Platform Layer: The platform layer abstracts even more complexity and provides managed services like databases, storage systems, and analytics tools.
-  Software Layer: At the software layer, AWS offers ready-to-use applications, such as email services, content management systems, and customer relationship management tools.

## What are the control plane and data plane responsible for in container abstraction?
-  Control Plane: The control plane is responsible for managing the overall orchestration and coordination of containers. It handles tasks such as provisioning, scheduling, scaling, and monitoring of containers.
-   Data Plane: The data plane, also known as the user plane or the data path, is responsible for handling the actual data flow within the containers. It manages the network traffic, load balancing, and communication between containers and external resources.

## Where does AWS Lambda fall in the layers of abstraction and what makes it so special?
- AWS Lambda falls under the Compute Layer of abstraction in AWS. It is a serverless compute service that allows you to run your code without provisioning or managing servers.

  ### Sources
  (Compute Abstractions on AWS: A Visual Story, Massimo Re Ferre, https://aws.amazon.com/blogs/architecture/compute-abstractions-on-aws-a-visual-story/)
  (ChatGPT, https://chat.openai.com/)
