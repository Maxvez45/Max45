# Environment Variable

if you have any confusion about the environment variable, please create an issue or contact me.

| Name | Description                                                                            | Default Value | Vercel                                                         | Optional |
| ---- |----------------------------------------------------------------------------------------| ------------- |----------------------------------------------------------------|---------|
| NEXT_PUBLIC_CHAT_FILES_UPLOAD_PATH | The path to store uploaded files.                                                      | public/uploads | /tmp                                                           | false   |
| NEXT_PUBLIC_CHAT_FILES_MAX_SIZE | The maximum value for file upload. If not set or set to 0, it means there is no limit. | 0 | 0                                                              | true    |
| DATABASE_URL | The url of supabase.                                                                   | |                                                                | false   |
| PRIMSA_MIGRATION_CONNECTION_STRING | The supabase url for prisma migration                                                  | |                                                                | false   |
| OPENAI_TYPE | The type of openai api. OPENAI or AZURE_OPENAI                                         | OPENAI | OPENAI                                                         | true    |
| OPENAI_API_KEY | The api key of openai.                                                                 | |                                                                | true    |
| OPENAI_API_MODEL | The api model of openai.                                                               | | gpt-3.5-turbo / gpt-4 / gpt-3.5-turbo-0613 / gpt-3.5-turbo-16k | true    |
| AZURE_OPENAI_API_KEY | The api key of azure openai.                                                           | |                                                                | true    |
| AZURE_OPENAI_API_DEPLOYMENT_NAME | The deployment name of azure openai.                                                   | |                                                                | true    |
| AZURE_OPENAI_API_EMBEDDINGS_DEPLOYMENT_NAME | The deployment name of azure openai embeddings.                                        | |                                                                | true    |
| AZURE_OPENAI_API_INSTANCE_NAME | The instance name of azure openai.                                                     | |                                                                | true    |
| AZURE_OPENAI_API_VERSION | The version of azure openai.                                                           | 2023-05-15 | 2023-05-15                                                     | true    |
| NEXTAUTH_URL | The url of nextauth.                                                                   | |                                                                | false   |
| NEXTAUTH_SECRET | The secret of nextauth.                                                                 | |                                                                | false   |
| GITHUB_ID | The github id of nextauth.                                                             | |                                                                | false   |
| GITHUB_SECRET | The github secret of nextauth.                                                         | |                                                                | false   |
| GOOGLE_CLIENT_ID | The google id of nextauth.                                                             | |                                                                | false   |
| GOOGLE_CLIENT_SECRET | The google secret of nextauth.                                                         | |                                                                | false   |
