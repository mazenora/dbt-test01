Welcome to your new dbt project!

### Using the starter project

Try running the following commands:
- dbt run
- dbt test


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](http://slack.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices


# My Tutorial Working with DBT  

## Install CLI:

conda create -n dbt python=3.8
conda activate dbt
pip install dbt
mkdir dbt
cd dbt
dbt init jaffle-shop
>> update dbt_project.yml with new profile name jaffle-shop
>> add BigQuery connection to profile.yml in .dbt/
cd jaffle_shop
dbt debug ##check if connection is OK
dbt run # run sample model
##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

$ git init
$ git add .
$ git commit -m "Create a dbt project"
$ git branch -M main
$ git remote add origin https://github.com/USERNAME/dbt-tutorial.git
$ git push -u origin main

## Working on model
git checkout -b add-customers-model
