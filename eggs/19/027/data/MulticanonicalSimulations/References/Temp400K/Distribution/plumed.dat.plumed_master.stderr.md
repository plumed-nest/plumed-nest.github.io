**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp400K/Distribution/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @28 : keyword ARG is compulsory for this action
[fv-az789-879:68325] *** Process received signal ***
[fv-az789-879:68325] Signal: Aborted (6)
[fv-az789-879:68325] Signal code:  (-6)
[fv-az789-879:68325] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feb02645330]
[fv-az789-879:68325] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feb0269eb2c]
[fv-az789-879:68325] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feb0264527e]
[fv-az789-879:68325] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feb026288ff]
[fv-az789-879:68325] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feb02aa5ff5]
[fv-az789-879:68325] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feb02abb0da]
[fv-az789-879:68325] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feb02aa5a55]
[fv-az789-879:68325] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feb02aa5a6f]
[fv-az789-879:68325] [ 8] plumed_master(+0x146dd)[0x555c1adc96dd]
[fv-az789-879:68325] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feb0262a1ca]
[fv-az789-879:68325] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feb0262a28b]
[fv-az789-879:68325] [11] plumed_master(+0x15365)[0x555c1adca365]
[fv-az789-879:68325] *** End of error message ***
</pre>
{% endraw %}
