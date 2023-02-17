app.kubernetes.io/name - This label identifies the name of the application.
app.kubernetes.io/component - This label identifies the specific component of the application, such as "web", "app", or "db".
app.kubernetes.io/instance - This label identifies the specific instance of the application, such as "dev" or "uat".
app.kubernetes.io/version - This label identifies the version of the application.
app.kubernetes.io/part-of - This label identifies the name of the parent application, if this application is part of a larger system.
app.kubernetes.io/managed-by - This label identifies the tool that manages this application, such as "Helm" or "Kustomize".
app.kubernetes.io/environment - This label identifies the environment in which the application is running, such as "prod" or "non-prod".
app.kubernetes.io/tier - This label identifies the specific tier of the application, such as "frontend", "backend", or "database".
app.kubernetes.io/stack - This label identifies the specific stack of the application, such as "LAMP" or "MEAN".
app.kubernetes.io/partition - This label identifies a specific partition of the application, such as "customer1" or "customer2", useful for multi-tenancy scenarios.
These labels allow for easy identification and management of Kubernetes resources, helping to ensure consistency and reduce errors when deploying and managing complex applications.




