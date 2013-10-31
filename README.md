
# Language constraints

All member variables are private
Last executed value is returned
Parenthesis as operation precedence

# Language primitives

function / fn

number (all 32bit floats unless otherwise specified)
	=> float
	=> int
	=> decimal

strings (char arrays)
collections
	min()
	=> vectors
	=> maps



Language features

ordered or keyed parameters
operator overloading
lambda syntax == fn syntax, stored as a fn variable

functionName (name:type, name2:type):returnType
	body
	last execution returns


parsing:



main(argc:int, argv:set<string>)
	print("Hello world")



=>

function
	name: main
	scope: nil
	flags
		nil // @private(protected), @public, @static
	arguments
		argument
			type: int
			name: argc
		argument
			type: set<string>
			name: argv
	body
		call
			package: global
			method: print
			arguments
				value: "Hello world"

call

=>

global.main
