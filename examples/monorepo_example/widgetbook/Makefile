.PHONY: version doctor

ifeq (, $(shell which ${FVM}))
	FLUTTER = flutter
	DART = dart
else
	FLUTTER = $(FVM) flutter
	DART = $(FVM) dart
endif

# build_runner (b)
b:
	fvm dart run build_runner build --delete-conflicting-outputs
