**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[runnervmgx7h7:11922] *** Process received signal ***
[runnervmgx7h7:11922] Signal: Aborted (6)
[runnervmgx7h7:11922] Signal code:  (-6)
[runnervmgx7h7:11922] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7823e45330]
[runnervmgx7h7:11922] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7823e9ec0c]
[runnervmgx7h7:11922] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7823e4527e]
[runnervmgx7h7:11922] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7823e288ff]
[runnervmgx7h7:11922] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f78242a5ff5]
[runnervmgx7h7:11922] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f78242bb0da]
[runnervmgx7h7:11922] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f78242a5a55]
[runnervmgx7h7:11922] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f78242a5a6f]
[runnervmgx7h7:11922] [ 8] plumed_master(+0x146dd)[0x55b6ca6696dd]
[runnervmgx7h7:11922] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7823e2a1ca]
[runnervmgx7h7:11922] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7823e2a28b]
[runnervmgx7h7:11922] [11] plumed_master(+0x15365)[0x55b6ca66a365]
[runnervmgx7h7:11922] *** End of error message ***
</pre>
{% endraw %}
