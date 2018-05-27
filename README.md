README
======

This is a partial replication and extension of the study reported in Shebani & Pulvermüller (2013).
We will use the same task with some minor methodological adjustments and test Swedish native L2 speakers of English.

The study will be pre-registered.


Description of repository
-------------------------

### Folder `exp-scripts_psychopy/` and subfolders

- `exp-scripts_psychopy/` contains all files (scripts and conditions files) needed to run the experiment.
	- `notes_running-experiment.md` contains notes for the RAs when running the experiment
	- `to-do_implementation.md` is a TO-DO list with stuff that needs to be solved for the experiment.
- `exp-scripts_psychopy/data/` is automatically created by PsychoPy to store all the data created when running the experiment.
- `exp-scripts_psychopy/stimuli/` contains the list of target verbs and R-scripts 
	- `create_experimental_lists.R` takes target and training items and generates randomized condition lists (under certain constraints, see the actual script).
-  `exp-scripts_psychopy/stimuli/presentation_lists/` contains the lists with randomly generated items which are read by the experiment (generated by `exp-scripts_psychopy/stimuli/create_experimental_lists.R`)


### Folder `Rfunctions/`

Contains R functions that are factored out from scripts to gain clarity.


REFs
----

Shebani, Z., & Pulvermüller, F. (2013). Moving the hands and feet specifically impairs working memory for arm- and leg-related action words. Cortex, 49(1), 222–231. https://doi.org/10.1016/j.cortex.2011.10.005

