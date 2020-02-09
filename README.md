# json-some-attributes-to-csv
## Read input.json entries array and output "id" & "name" values as CSV.

jq '.[] | [.id, .name] | @csv' input.json
