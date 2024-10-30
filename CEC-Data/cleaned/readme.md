### parties

| name | type |
|--------------|--------|
| party_number | string |
| party_name   | string |
| party_color  | string |


### districts

| name | type |
|--------------|--------|
| district_id | int64 
| district_number | string
| district_name | string


### divisions

| name | type |
|--------------|--------|
| district_number | string |
| division_alias | string |
| division_number | string |
| division_prot_id | string |


### division_votes

| name | type |
|--------------|--------|
| division_alias | string |
| party_number | string |
| votes | int64 |
| percent | float64 |


### division_votes_flatten

| name | type |
|--------------|--------|
| division_alias | string |
| division_number | string |
| division_prot_id | string |
| district_number | string |
| district_id | int64 |
| district_name | string |
| party_number | string |
| party_name | string |
| party_color | string |
| votes | int64 |
| percent | float64 |
