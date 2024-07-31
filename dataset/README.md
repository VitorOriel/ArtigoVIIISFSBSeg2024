# Helm Extractor

The bashcript provided in this directory was responsible to retrieve the dataset from artifacthub.io, used into the tests.

In order to extract the dataset, you must:
1. Have a deployed Kubernetes cluster in the environment where the extraction will run;
2. Create an account in the [Artifacthub.io](https://artifacthub.io/)
3. Navigate to Control Panel >> Settings >> API Keys, and generate an API Key
4. With both `api-key-id` and `api-key-secret` in hands, export to environment variables:
    - `export API_KEY_ID=<api-key-id>`
    - `export API_KEY_SECRET=<api-key-secret>`
5. Run the extractor with `./extractor.sh`

See the youtube video below for this extraction phase:
https://www.youtube.com/watch?v=nv021DnKymc
