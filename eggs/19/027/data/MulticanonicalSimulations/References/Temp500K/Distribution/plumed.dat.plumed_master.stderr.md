**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp500K/Distribution/plumed.dat   
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
[fv-az789-879:68455] *** Process received signal ***
[fv-az789-879:68455] Signal: Aborted (6)
[fv-az789-879:68455] Signal code:  (-6)
[fv-az789-879:68455] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd6c0045330]
[fv-az789-879:68455] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd6c009eb2c]
[fv-az789-879:68455] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd6c004527e]
[fv-az789-879:68455] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd6c00288ff]
[fv-az789-879:68455] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd6c04a5ff5]
[fv-az789-879:68455] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd6c04bb0da]
[fv-az789-879:68455] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd6c04a5a55]
[fv-az789-879:68455] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd6c04a5a6f]
[fv-az789-879:68455] [ 8] plumed_master(+0x146dd)[0x5607eaccb6dd]
[fv-az789-879:68455] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd6c002a1ca]
[fv-az789-879:68455] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd6c002a28b]
[fv-az789-879:68455] [11] plumed_master(+0x15365)[0x5607eaccc365]
[fv-az789-879:68455] *** End of error message ***
</pre>
{% endraw %}
