**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:11437] *** Process received signal ***
[pkrvmpptgkbjq6m:11437] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11437] Signal code:  (-6)
[pkrvmpptgkbjq6m:11437] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1071045330]
[pkrvmpptgkbjq6m:11437] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f107109eb2c]
[pkrvmpptgkbjq6m:11437] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f107104527e]
[pkrvmpptgkbjq6m:11437] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f10710288ff]
[pkrvmpptgkbjq6m:11437] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f10714a5ff5]
[pkrvmpptgkbjq6m:11437] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f10714bb0da]
[pkrvmpptgkbjq6m:11437] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f10714a5a55]
[pkrvmpptgkbjq6m:11437] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f10714a5a6f]
[pkrvmpptgkbjq6m:11437] [ 8] plumed_master(+0x146dd)[0x55e173b036dd]
[pkrvmpptgkbjq6m:11437] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f107102a1ca]
[pkrvmpptgkbjq6m:11437] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f107102a28b]
[pkrvmpptgkbjq6m:11437] [11] plumed_master(+0x15365)[0x55e173b04365]
[pkrvmpptgkbjq6m:11437] *** End of error message ***
</pre>
{% endraw %}
