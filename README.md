# Jenkins Pipeline Examples by Practice
Lessons to learn Jenkins pipeline-as-code by practice.

## Where to start?
1. You should have access to Jenkins instance.

2. Ensure, in the above Jenkins instance, with your login creds, it is possible to,

* Create a pipeline job
* Use `Replay` option in the pipeline job

## How do I use the examples to practice?

### Setup Pipeline job
1. Create a new pipeline job.

2. In the new job, use this repo in the `Pipeline Script from SCM` section.

3. Retain the rest of the config as is and save the job.

### Fix the errors in the pipeline script

1. Run the pipeline job. 

2. Navigate to the passed job and select the `Replay` option. This should bring up the contents of the main pipeline script in an in-line editor.

3. In the in-line editor, replace the contents with the content of Jenkinsfile from each folder, starting with `01_fix_node`.

4. With the replaced content, `Run` the script, analyze the build log (i.e. console output) and fix the errors.

Hint:
Inside each folder, there is a `README` with the hint on how to fix the errors.















