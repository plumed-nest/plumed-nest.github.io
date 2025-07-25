**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @113 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:08407] *** Process received signal ***
[pkrvmpptgkbjq6m:08407] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08407] Signal code:  (-6)
[pkrvmpptgkbjq6m:08407] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f79ae645330]
[pkrvmpptgkbjq6m:08407] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f79ae69eb2c]
[pkrvmpptgkbjq6m:08407] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f79ae64527e]
[pkrvmpptgkbjq6m:08407] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f79ae6288ff]
[pkrvmpptgkbjq6m:08407] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f79aeaa5ff5]
[pkrvmpptgkbjq6m:08407] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f79aeabb0da]
[pkrvmpptgkbjq6m:08407] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f79aeaa5a55]
[pkrvmpptgkbjq6m:08407] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f79aeaa5a6f]
[pkrvmpptgkbjq6m:08407] [ 8] plumed_master(+0x146dd)[0x564d893136dd]
[pkrvmpptgkbjq6m:08407] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f79ae62a1ca]
[pkrvmpptgkbjq6m:08407] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f79ae62a28b]
[pkrvmpptgkbjq6m:08407] [11] plumed_master(+0x15365)[0x564d89314365]
[pkrvmpptgkbjq6m:08407] *** End of error message ***
</pre>
{% endraw %}
