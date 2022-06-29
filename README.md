# Tic-Tac-Toe-engine
Consists of MCTS implementation on Tic-Tac-Toe <br/>
the engine has various commands which allows you to <br/>
play against it from given position, analyse different positions and also specify details. <br/>
It uses MCTS (Monte Carlo Tree Search) where it conducts random playouts in a systematic manner. <br/>
commands work as follows <br/>
help()                 -> will give list of all commands (only 7 including help()...) <br/>
play_start().ON        -> to play against the engine from start (toggle to OFF if you don't want engine analysis) <br/>
play_from().ON         -> to play against the engine from specified position (same thing for toggling) <br/>
                          after passing the command you have to specify the position. <br/>
analyse()              -> to get engine analysis for a particular position, after passing the command you have to specify the position.<br/>
set playouts_primary   -> setting primary playouts (see analyse function's working) default 10 (specify after passing command) <br/>
set playouts_secondary -> setting secondary playouts (see analyse function's working) default 10 (specify after passing command) <br/>
terminate()            -> exit the main function <br/>
(All header files (.h files) and cpp files have been written by the author (i.e. N-dimensions)) <br/>
