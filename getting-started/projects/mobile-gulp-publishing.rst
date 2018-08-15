Migrate Moodle Mobile publishing scripts to Gulp tasks
------------------------------------------------------

Right now the Mobile app uses `several scripts`_ for common tasks related to publishing.

Those scripts should be migrated to Gulp tasks so they are available among the other tasks already implemented.

Tasks
^^^^^

* Migrate the prepare-release-version.sh script to gulp task
* Migrate the prepare-release-integration.sh script to gulp task
* Improve previous scripts to compile the resulting app via Phonegap Build API
* Migrate the rest of scripts that synchronizes language translations


Requirement for prospective student
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

We require prospective students to set-up a local development environment of the Mobile app (and run it locally) following this documentation: Setting_up_your_development_environment_for_Moodle_Mobile_2, students must provide a video or detailed screenshots including a detailed explanation of what they did to run the app locally.

======================  ==================
Skills required         Javascript
Difficulty level        Medium
Possible mentor         Juan Leyva
======================  ==================

:: _`several scripts`: https://github.com/moodlehq/moodlemobile-scripts
