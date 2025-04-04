# Spring Boot Banner

This repository contains a custom ASCII banner for use with Spring Boot applications.

## Usage

Place the `banner.txt` file in the `src/main/resources` directory of your Spring Boot project. It will automatically be displayed in the console on application startup.

## Features

- Dynamic placeholders for application and system properties
- ANSI color codes for enhanced readability
- Clean and professional layout

## Example placeholders used

\`\`\`
\${AnsiColor.BRIGHT_GREEN}Application:         \${AnsiColor.WHITE}\${app.name}
\${AnsiColor.BRIGHT_GREEN}Version:             \${AnsiColor.WHITE}\${app.version}
\${AnsiColor.BRIGHT_GREEN}Spring Boot:         \${AnsiColor.WHITE}\${spring-boot.version}
\${AnsiColor.BRIGHT_GREEN}Java:                \${AnsiColor.WHITE}\${java.version}
\${AnsiColor.BRIGHT_YELLOW}User:                \${AnsiColor.WHITE}\${user.name}
\${AnsiColor.BRIGHT_YELLOW}Dir:                 \${AnsiColor.WHITE}\${user.dir}
\${AnsiColor.BRIGHT_YELLOW}Encoding:            \${AnsiColor.WHITE}\${file.encoding}
\${AnsiColor.BRIGHT_YELLOW}Time Zone:           \${AnsiColor.WHITE}\${user.timezone}
\${AnsiColor.BRIGHT_YELLOW}OS:                  \${AnsiColor.WHITE}\${os.name} \${os.version} (\${os.arch})
\${AnsiColor.DEFAULT}
\`\`\`

## Banner preview

\`\`\`
________              _____                    ________            _____     _______
__  ___/_________________(_)_____________ _    ___  __ )_____________  /_    ___    |_______________
_____ \___  __ \_  ___/_  /__  __ \_  __ \`/    __  __  |  __ \  __ \  __/    __  /| |__  __ \__  __ \
____/ /__  /_/ /  /   _  / _  / / /  /_/ /     _  /_/ // /_/ / /_/ / /_      _  ___ |_  /_/ /_  /_/ /
/____/ _  .___//_/    /_/  /_/ /_/_\__, /      /_____/ \____/\____/\__/      /_/  |_|  .___/_  .___/
       /_/                        /____/                                            /_/     /_/
\`\`\`
