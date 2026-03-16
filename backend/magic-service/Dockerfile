FROM alpine

ARG GOLANG_VERSION
ARG DOCKERHUB_LIBRARY_IMAGE_PREFIX=public.ecr.aws/docker/library/
ARG GOPROXY
ARG APK_MIRROR=mirrors.aliyun.com
ARG TZ=Asia/Shanghai
ARG COMPOSER_MIRROR=https://mirrors.aliyun.com/composer/
ARG PYTHON_VERSION=3.12
ARG PIP_INDEX_URL=https://pypi.tuna.tsinghua.edu.cn/simple
ARG DEBIAN_VERSION=trixie
ARG APT_MIRROR=mirrors.aliyun.com
ARG NODE_VERSION=24
ARG NODEJS_MIRROR=https://mirrors.aliyun.com/nodejs-release/
ARG NPM_REGISTRY=https://registry.npmmirror.com
ARG CI_COMMIT_SHA="未知"

RUN \
    echo GOLANG_VERSION=${GOLANG_VERSION} && \
    echo APK_MIRROR=${APK_MIRROR} && \
    echo TZ=${TZ} && \
    echo COMPOSER_MIRROR=${COMPOSER_MIRROR} && \
    echo PYTHON_VERSION=${PYTHON_VERSION} && \
    echo PIP_INDEX_URL=${PIP_INDEX_URL} && \
    echo DEBIAN_VERSION=${DEBIAN_VERSION} && \
    echo APT_MIRROR=${APT_MIRROR} && \
    echo NODE_VERSION=${NODE_VERSION} && \
    echo NODEJS_MIRROR=${NODEJS_MIRROR} && \
    echo NPM_REGISTRY=${NPM_REGISTRY} && \
    echo CI_COMMIT_SHA=${CI_COMMIT_SHA}


