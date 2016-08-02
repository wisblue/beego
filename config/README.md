#multiple lines config:
key = `
line1
line2
line3`

# string array format
# Strings(key string) []string
key = s1;s2;s3

# return config as map
# GetSection(section string) (map[string]string, error) 

# section
# sec::key
[sec]
key = value
