-include ../rules.mk

.PHONY: all
all: python-builder python-env-img python-env-3.7-img python-env-3.8-img python-env-3.9-img python-env-3.10-img

python-env-img-buildargs := --build-arg PY_BASE_IMG=python:3.7.17-alpine

python-env-3.7-img-buildargs := --build-arg PY_BASE_IMG=python:3.7.17-alpine

python-env-3.8-img-buildargs := --build-arg PY_BASE_IMG=python:3.8.19-alpine

python-env-3.9-img-buildargs := --build-arg PY_BASE_IMG=python:3.9.19-alpine

python-env-3.10-img-buildargs := --build-arg PY_BASE_IMG=python:3.10.14-alpine

python-env-img: Dockerfile

python-env-3.7-img: Dockerfile

python-env-3.8-img: Dockerfile

python-env-3.9-img: Dockerfile

python-env-3.10-img: Dockerfile
