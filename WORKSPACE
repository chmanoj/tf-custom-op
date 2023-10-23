load("//tf:tf_configure.bzl", "tf_configure")
load("//gpu:cuda_configure.bzl", "cuda_configure")

tf_configure(name = "local_config_tf")

cuda_configure(name = "local_config_cuda")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
	    name = "platforms",
	        urls = [
			        "https://mirror.bazel.build/github.com/bazelbuild/platforms/releases/download/0.0.7/platforms-0.0.7.tar.gz",
				        "https://github.com/bazelbuild/platforms/releases/download/0.0.7/platforms-0.0.7.tar.gz",
					    ],
		    sha256 = "3a561c99e7bdbe9173aa653fd579fe849f1d8d67395780ab4770b1f381431d51",
)
