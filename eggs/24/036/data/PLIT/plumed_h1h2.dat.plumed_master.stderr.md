**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @48 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:06526] *** Process received signal ***
[pkrvmpptgkbjq6m:06526] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06526] Signal code:  (-6)
[pkrvmpptgkbjq6m:06526] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4ce6645330]
[pkrvmpptgkbjq6m:06526] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4ce669eb2c]
[pkrvmpptgkbjq6m:06526] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4ce664527e]
[pkrvmpptgkbjq6m:06526] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4ce66288ff]
[pkrvmpptgkbjq6m:06526] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4ce6aa5ff5]
[pkrvmpptgkbjq6m:06526] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4ce6abb0da]
[pkrvmpptgkbjq6m:06526] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4ce6aa5a55]
[pkrvmpptgkbjq6m:06526] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4ce6aa5a6f]
[pkrvmpptgkbjq6m:06526] [ 8] plumed_master(+0x146dd)[0x5586b3e1b6dd]
[pkrvmpptgkbjq6m:06526] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4ce662a1ca]
[pkrvmpptgkbjq6m:06526] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4ce662a28b]
[pkrvmpptgkbjq6m:06526] [11] plumed_master(+0x15365)[0x5586b3e1c365]
[pkrvmpptgkbjq6m:06526] *** End of error message ***
</pre>
{% endraw %}
