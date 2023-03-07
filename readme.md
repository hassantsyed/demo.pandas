# Part 1
## Pandas code generation helper.
1. Follow along the first part of the notebook to use the hosted, fintetuned model. 


# Part 2
## Running the Code Generation Model locally.
1. Install python requirements.txt
2. download the model weights. This download is ~30Gb, and can take several hours.
wget -P checkpoints https://storage.googleapis.com/sfr-codegen-research/checkpoints/codegen-16B-mono.tar.gz && tar -xvf checkpoints/codegen-16B-mono.tar.gz -C checkpoints/
3. That should create a folder called checkpoints/codegen-16B-mono, confirm it exists.
4. You should now be able to follow along with the notebook.