# 0.0.1
extract the import utils from rap project

# 0.0.2
fix JSON5 import, from `import * as JSON5 from 'json5'` to `import JSON5 from 'json5'`

# 0.0.3
fix convert YAPI type, when type is array and not define items type, the type value is ['array', 'null']
