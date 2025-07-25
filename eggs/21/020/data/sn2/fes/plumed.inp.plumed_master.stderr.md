**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @43 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:10132] *** Process received signal ***
[pkrvmpptgkbjq6m:10132] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10132] Signal code:  (-6)
[pkrvmpptgkbjq6m:10132] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4a80645330]
[pkrvmpptgkbjq6m:10132] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4a8069eb2c]
[pkrvmpptgkbjq6m:10132] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4a8064527e]
[pkrvmpptgkbjq6m:10132] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4a806288ff]
[pkrvmpptgkbjq6m:10132] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4a80aa5ff5]
[pkrvmpptgkbjq6m:10132] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4a80abb0da]
[pkrvmpptgkbjq6m:10132] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4a80aa5a55]
[pkrvmpptgkbjq6m:10132] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4a80aa5a6f]
[pkrvmpptgkbjq6m:10132] [ 8] plumed_master(+0x146dd)[0x562aebf226dd]
[pkrvmpptgkbjq6m:10132] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4a8062a1ca]
[pkrvmpptgkbjq6m:10132] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4a8062a28b]
[pkrvmpptgkbjq6m:10132] [11] plumed_master(+0x15365)[0x562aebf23365]
[pkrvmpptgkbjq6m:10132] *** End of error message ***
</pre>
{% endraw %}
