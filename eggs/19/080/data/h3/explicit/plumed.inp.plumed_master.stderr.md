**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/explicit/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:69078] *** Process received signal ***
[pkrvmf6wy0o8zjz:69078] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:69078] Signal code:  (-6)
[pkrvmf6wy0o8zjz:69078] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f914f845330]
[pkrvmf6wy0o8zjz:69078] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f914f89eb2c]
[pkrvmf6wy0o8zjz:69078] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f914f84527e]
[pkrvmf6wy0o8zjz:69078] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f914f8288ff]
[pkrvmf6wy0o8zjz:69078] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f914fca5ff5]
[pkrvmf6wy0o8zjz:69078] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f914fcbb0da]
[pkrvmf6wy0o8zjz:69078] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f914fca5a55]
[pkrvmf6wy0o8zjz:69078] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f914fca5a6f]
[pkrvmf6wy0o8zjz:69078] [ 8] plumed_master(+0x146dd)[0x55bc771836dd]
[pkrvmf6wy0o8zjz:69078] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f914f82a1ca]
[pkrvmf6wy0o8zjz:69078] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f914f82a28b]
[pkrvmf6wy0o8zjz:69078] [11] plumed_master(+0x15365)[0x55bc77184365]
[pkrvmf6wy0o8zjz:69078] *** End of error message ***
</pre>
{% endraw %}
