# Grant_Data


1. flat and structured are for cambio-doc-upload

About: entirely llm based q&a matching

Results: tested on all the files until a time out error occured w/ google auth (not really could have fixed with adding a file)
the output has inconsistiencies the llm alone does not do a good job at differentiating between q and a


2. rule_based files

About: use a hybrid mix of rule-based regex matching and llm generation for q&a finding and category matching.

Results: tested on only 2 docs in a test folder
seems to do a better job than just using the llm
only issue is some text/questions repeat and don't have answers - but the ones that are correctly matched also have pretty good category matching.
also duplicates exist

3. full_rules files
Same as above but tested on all docs in grant_training_data
