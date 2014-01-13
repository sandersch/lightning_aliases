!SLIDE

# Simulate OSX's pbcopy and pbpaste on other platforms

    @@@ Shell
    if [ ! $(uname -s) = "Darwin" ]; then
      alias  pbcopy='xsel --clipboard --input'
      alias pbpaste='xsel --clipboard --output'
    fi

!SLIDE

# Conditionally Defined Aliases

!SLIDE

# Set default options for commands

    @@@ Shell
    alias grep='grep --color=auto --line-number'

!SLIDE

# Functions as Aliases

