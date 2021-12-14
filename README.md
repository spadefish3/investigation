# investigation
-
One row is one transaction:
from = address
to = address
hash = transaction hash
blockNumber
timeStamp
cluster_id = generated id number, connects all addresses that are in any way connected through a tx
cluster_size = how many addresses connected in the cluster
connections_to_other_addresses = how many direct tx connections does the from address have. For example if the address in "from" column has sent eth to 5 other addresses, then this column has value 5
number_of_actions_from = how many interactions the "from" address has done with GEARBOX protocol (source: https://docs.google.com/spreadsheets/d/1xQzl_pqFtP8XLZ0cx1ds-X_nWu68sthTg8ELKEf3QDk/)
number_of_actions_to = how many interactions the "to" address has done with GEARBOX protocol
