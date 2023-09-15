# FamixTraitsVisualization

Graphical presentations of Famix Traits.

To load this project in a Moose image (Moose 9 to 11):
```smalltalk
[ Metacello new
	baseline: 'FamixTraitsVisualization';
	repository: 'github://moosetechnology/FamixTraitsVisualization:main/src';
	load ]
	on: MCMergeOrLoadWarning
	do: [ :warning | warning load ]
