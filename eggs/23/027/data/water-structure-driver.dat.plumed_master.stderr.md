**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  water-structure-driver.dat   
Download: [zipped raw stdout](water-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](water-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @179 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:07504] *** Process received signal ***
[pkrvmpptgkbjq6m:07504] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07504] Signal code:  (-6)
[pkrvmpptgkbjq6m:07504] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc1a4a45330]
[pkrvmpptgkbjq6m:07504] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc1a4a9eb2c]
[pkrvmpptgkbjq6m:07504] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc1a4a4527e]
[pkrvmpptgkbjq6m:07504] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc1a4a288ff]
[pkrvmpptgkbjq6m:07504] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc1a4ea5ff5]
[pkrvmpptgkbjq6m:07504] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc1a4ebb0da]
[pkrvmpptgkbjq6m:07504] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc1a4ea5a55]
[pkrvmpptgkbjq6m:07504] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc1a4ea5a6f]
[pkrvmpptgkbjq6m:07504] [ 8] plumed_master(+0x146dd)[0x5623612e06dd]
[pkrvmpptgkbjq6m:07504] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc1a4a2a1ca]
[pkrvmpptgkbjq6m:07504] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc1a4a2a28b]
[pkrvmpptgkbjq6m:07504] [11] plumed_master(+0x15365)[0x5623612e1365]
[pkrvmpptgkbjq6m:07504] *** End of error message ***
</pre>
{% endraw %}
