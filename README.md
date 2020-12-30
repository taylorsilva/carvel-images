# Carvel Images

This repo publishes images that contain the following [Carvel apps](https://carvel.dev):

* [ytt](https://github.com/vmware-tanzu/carvel-ytt) | ![ytt image build status](https://ci.concourse-ci.org/api/v1/teams/tay/pipelines/carvel-apps/jobs/ytt/badge)
* [kapp](https://github.com/vmware-tanzu/carvel-kapp) | ![kapp image build status](https://ci.concourse-ci.org/api/v1/teams/tay/pipelines/carvel-apps/jobs/kapp/badge)
* [kbld](https://github.com/vmware-tanzu/carvel-kbld) | ![kbld image build status](https://ci.concourse-ci.org/api/v1/teams/tay/pipelines/carvel-apps/jobs/kbld/badge)
* [kwt](https://github.com/vmware-tanzu/carvel-kwt) | ![kwt image build status](https://ci.concourse-ci.org/api/v1/teams/tay/pipelines/carvel-apps/jobs/kwt/badge)
* [imgpkg](https://github.com/vmware-tanzu/carvel-imgpkg) | ![imgpkg image build status](https://ci.concourse-ci.org/api/v1/teams/tay/pipelines/carvel-apps/jobs/imgpkg/badge)
* [vendir](https://github.com/vmware-tanzu/carvel-vendir) | ![vendir image build status](https://ci.concourse-ci.org/api/v1/teams/tay/pipelines/carvel-apps/jobs/vendir/badge)


You can download a single image with the latest version of all apps with:
![vendir image build status](https://ci.concourse-ci.org/api/v1/teams/tay/pipelines/carvel-apps/jobs/vendir/badge)
```
docker pull taylorsilva/carvel-apps
```

You can pull an image with an individual app using:
```
docker pull taylorsilva/carvel-ytt
docker pull taylorsilva/carvel-kapp
docker pull taylorsilva/carvel-kbld
docker pull taylorsilva/carvel-kwt
docker pull taylorsilva/carvel-imgpkg
docker pull taylorsilva/carvel-vendir
```
