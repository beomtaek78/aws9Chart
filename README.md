# My Helm Chart

## Overview
설명: 이 Helm chart는 nginx pod 와 LoadBalancer 를 배포합니다.
사전에 metallb 를 설치해 두어야 합니다

## Installation

```bash
helm repo add myrepo https://beomtaek78.github.io/aws9Chart
helm install my-release myrepo/nginx-chart
