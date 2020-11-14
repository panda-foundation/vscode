# vscode

TO-DO

functions
call
declare var const
ident
[]
.
number

		{
			"begin": "\\b(var)\\s+",
			"beginCaptures": {
				"1": {
					"name": "keyword.var.go"
				}
			},
			"end": "(?!\\G)",
			"patterns": [
				{
					"include": "#variables"
				}
			]
		},

        param list