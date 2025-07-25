**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_2D_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:08368] *** Process received signal ***
[pkrvmpptgkbjq6m:08368] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08368] Signal code:  (-6)
[pkrvmpptgkbjq6m:08368] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff7f9645330]
[pkrvmpptgkbjq6m:08368] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff7f969eb2c]
[pkrvmpptgkbjq6m:08368] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff7f964527e]
[pkrvmpptgkbjq6m:08368] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff7f96288ff]
[pkrvmpptgkbjq6m:08368] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff7f9aa5ff5]
[pkrvmpptgkbjq6m:08368] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff7f9abb0da]
[pkrvmpptgkbjq6m:08368] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff7f9aa5a55]
[pkrvmpptgkbjq6m:08368] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff7f9aa5a6f]
[pkrvmpptgkbjq6m:08368] [ 8] plumed_master(+0x146dd)[0x555c9cc7d6dd]
[pkrvmpptgkbjq6m:08368] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff7f962a1ca]
[pkrvmpptgkbjq6m:08368] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff7f962a28b]
[pkrvmpptgkbjq6m:08368] [11] plumed_master(+0x15365)[0x555c9cc7e365]
[pkrvmpptgkbjq6m:08368] *** End of error message ***
</pre>
{% endraw %}
