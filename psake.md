never had issue with nant or mmsbuild.
not afraid of angle brackets

nant abandoned.

psake
good: dependency tracking, property handling

bad
maybe my unfamiliarity with powershell/psake

documentation
not geared for build
silent failing default for external (need to wrap with exec{})
hard to duplicate, copy item can create directory the first time and fail but succeed the next time
eager to fail (removing non-existent directory)
hard to build file list (preserving structure) like nants
built in file copy won't preserve directory properly, either too much or not at all. (without changing directories)
need to resort to xcopy

what can be done?

more helpers
