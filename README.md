# Sidebar Record Copy Environment

Allow copy a record to another environment.

## Configuration

Requires a configuration in the plugin:
- CurrentUserAccessToken permissions.
- Load environments.
- Add models (comma delimited).

# Considerations
- The record to be copied must have the same field structure and model in the another environment.
- The plugin only supports copying the values ​​of all basic fields types, 'link' and 'file' types.
- The plugin does not copy values ​​from these fields types: gallery, multiple, rich_text, structured_text
- For the 'link' field type, the linked record must have a field with the unique constraint and also exist in the another environment.
- For field type 'file', the file will be created in the other environment when it doesn't exist

# TODO
- Create the record in the another environment in case it dows not exits for the 'link' field type.
- Support all fields types.

