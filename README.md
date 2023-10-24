-To run on existing VPC
  ```sh
  export tf_state_path=<Path to terraform state file>
  export tv_vars-path=<Path to terraform.tfvars>
  pytest -vs
```

-To create VPC, run tests, and destroy VPC
  ```sh
  export tf_state_path=<Path to terraform state file>
  export tv_vars-path=<Path to terraform.tfvars>
  pytest --tif-directory=<Path to main.ft>    
  ```
