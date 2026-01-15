**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Uracil/iMetaD/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[runnervmmtnos:33056] *** Process received signal ***
[runnervmmtnos:33056] Signal: Aborted (6)
[runnervmmtnos:33056] Signal code:  (-6)
[runnervmmtnos:33056] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f76cc445330]
[runnervmmtnos:33056] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f76cc49eb2c]
[runnervmmtnos:33056] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f76cc44527e]
[runnervmmtnos:33056] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f76cc4288ff]
[runnervmmtnos:33056] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f76cc8a5ff5]
[runnervmmtnos:33056] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f76cc8bb0da]
[runnervmmtnos:33056] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f76cc8a5a55]
[runnervmmtnos:33056] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f76cc8a5a6f]
[runnervmmtnos:33056] [ 8] plumed_master(+0x146dd)[0x55e12e5386dd]
[runnervmmtnos:33056] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f76cc42a1ca]
[runnervmmtnos:33056] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f76cc42a28b]
[runnervmmtnos:33056] [11] plumed_master(+0x15365)[0x55e12e539365]
[runnervmmtnos:33056] *** End of error message ***
</pre>
{% endraw %}
