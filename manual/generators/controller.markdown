Generators -- controller
{: .document-title}


## Usage

    

    rails generate hobo:controller NAME


## Options

    

    -t, [--test-framework=NAME]  # Test framework to be invoked
                                 # Default: test_unit
        [--helpers]              # Generates helper files
                                 # Default: true


## Runtime options

    

    -f, [--force]    # Overwrite files that already exist
    -s, [--skip]     # Skip files that already exist
    -p, [--pretend]  # Run but do not make any changes
    -q, [--quiet]    # Supress status output


## Description

    


      Creates a Hobo model controller.   Called from the Hobo `resource` generator.
