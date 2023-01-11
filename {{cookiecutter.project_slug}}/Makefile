version?=local
.PHONY: build
build:
	./gradlew build

.PHONY: test
test:
	./gradlew check

.PHONY: run
publish:
	./gradlew publish -Prevision=${version}

.PHONY: deploy-local
deploy-local:
	./gradlew publishToMavenLocal -Prevision=${version}
