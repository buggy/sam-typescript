build-HelloWorldFunction:
	# echo "Folder: ${PWD}" > "$(ARTIFACTS_DIR)/output.txt"
	echo "Folder: ${PWD}" > "/tmp/output.txt"
	echo "Workspace Folder: ${WORKSPACE_FOLDER}" > "/tmp/output.txt"
	export >> /tmp/output.txt
	ls -al "${PWD}" >> /tmp/output.txt
	npm --prefix "${PWD}" run webpack -- --entry ./src/hello-world/app.ts --output-path "$(ARTIFACTS_DIR)" --output-filename app.js
