
docker_images=[
"shikanon096/kubeflow-images-public.ingress-setup:latest",
"shikanon096/kubeflow-images-public.admission-webhook:v20190520-v0-139-gcee39dbc-dirty-0d8f4c",
"shikanon096/kubeflow-images-public.kubernetes-sigs.application:1.0-beta",
"shikanon096/kubeflow-images-public.centraldashboard:v20190823-v0.6.0-rc.0-69-gcb7dab59",
"shikanon096/kubeflow-images-public.jupyter-web-app:9419d4d",
"shikanon096/kubeflow-images-public.katib.v1alpha2.katib-controller:v0.6.0-rc.0",
"shikanon096/kubeflow-images-public.katib.v1alpha2.katib-manager:v0.6.0-rc.0",
"shikanon096/kubeflow-images-public.katib.v1alpha2.katib-manager-rest:v0.6.0-rc.0",
"shikanon096/kubeflow-images-public.katib.v1alpha2.suggestion-bayesianoptimization:v0.6.0-rc.0",
"shikanon096/kubeflow-images-public.katib.v1alpha2.suggestion-grid:v0.6.0-rc.0",
"shikanon096/kubeflow-images-public.katib.v1alpha2.suggestion-hyperband:v0.6.0-rc.0",
"shikanon096/kubeflow-images-public.katib.v1alpha2.suggestion-nasrl:v0.6.0-rc.0",
"shikanon096/kubeflow-images-public.katib.v1alpha2.suggestion-random:v0.6.0-rc.0",
"shikanon096/kubeflow-images-public.katib.v1alpha2.katib-ui:v0.6.0-rc.0",
"shikanon096/kubeflow-images-public.metadata:v0.1.8",
"shikanon096/kubeflow-images-public.metadata-frontend:v0.1.8",
"shikanon096/ml-pipeline.api-server:0.1.23",
"shikanon096/ml-pipeline.persistenceagent:0.1.23",
"shikanon096/ml-pipeline.scheduledworkflow:0.1.23",
"shikanon096/ml-pipeline.frontend:0.1.23",
"shikanon096/ml-pipeline.viewer-crd-controller:0.1.23",
"shikanon096/kubeflow-images-public.notebook-controller:v20190603-v0-175-geeca4530-e3b0c4",
"shikanon096/kubeflow-images-public.profile-controller:v20190619-v0-219-gbd3daa8c-dirty-1ced0e",
"shikanon096/kubeflow-images-public.kfam:v20190612-v0-170-ga06cdb79-dirty-a33ee4",
"shikanon096/kubeflow-images-public.pytorch-operator:v1.0.0-rc.0",
"shikanon096/google_containers.spartakus-amd64:v1.1.0",
"shikanon096/kubeflow-images-public.tf_operator:v0.6.0.rc0",
"shikanon096/arrikto.kubeflow.oidc-authservice:v0.2"
]


ali_image = [
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.ingress-setup:latest",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.admission-webhook:v20190520-v0-139-gcee39dbc-dirty-0d8f4c",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.kubernetes-sigs.application:1.0-beta",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.centraldashboard:v20190823-v0.6.0-rc.0-69-gcb7dab59",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.jupyter-web-app:9419d4d",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.katib.v1alpha2.katib-controller:v0.6.0-rc.0",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.katib.v1alpha2.katib-manager:v0.6.0-rc.0",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.katib.v1alpha2.katib-manager-rest:v0.6.0-rc.0",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.katib.v1alpha2.suggestion-bayesianoptimization:v0.6.0-rc.0",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.katib.v1alpha2.suggestion-grid:v0.6.0-rc.0",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.katib.v1alpha2.suggestion-hyperband:v0.6.0-rc.0",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.katib.v1alpha2.suggestion-nasrl:v0.6.0-rc.0",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.katib.v1alpha2.suggestion-random:v0.6.0-rc.0",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.katib.v1alpha2.katib-ui:v0.6.0-rc.0",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.metadata:v0.1.8",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.metadata-frontend:v0.1.8",
"registry.cn-shenzhen.aliyuncs.com/shikanon/ml-pipeline.api-server:0.1.23",
"registry.cn-shenzhen.aliyuncs.com/shikanon/ml-pipeline.persistenceagent:0.1.23",
"registry.cn-shenzhen.aliyuncs.com/shikanon/ml-pipeline.scheduledworkflow:0.1.23",
"registry.cn-shenzhen.aliyuncs.com/shikanon/ml-pipeline.frontend:0.1.23",
"registry.cn-shenzhen.aliyuncs.com/shikanon/ml-pipeline.viewer-crd-controller:0.1.23",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.notebook-controller:v20190603-v0-175-geeca4530-e3b0c4",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.profile-controller:v20190619-v0-219-gbd3daa8c-dirty-1ced0e",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.kfam:v20190612-v0-170-ga06cdb79-dirty-a33ee4",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.pytorch-operator:v1.0.0-rc.0",
"registry.cn-shenzhen.aliyuncs.com/shikanon/google_containers.spartakus-amd64:v1.1.0",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.tf_operator:v0.6.0.rc0",
"registry.cn-shenzhen.aliyuncs.com/shikanon/arrikto.kubeflow.oidc-authservice:v0.2",
"registry.cn-shenzhen.aliyuncs.com/shikanon/kubeflow-images-public.katib.v1alpha2.metrics-collector:v0.1.2-alpha-289-g14dad8b"
]