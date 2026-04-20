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
[runnervmeorf1:05555] *** Process received signal ***
[runnervmeorf1:05555] Signal: Aborted (6)
[runnervmeorf1:05555] Signal code:  (-6)
[runnervmeorf1:05555] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb566845330]
[runnervmeorf1:05555] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb56689eb2c]
[runnervmeorf1:05555] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb56684527e]
[runnervmeorf1:05555] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb5668288ff]
[runnervmeorf1:05555] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb566ca5ff5]
[runnervmeorf1:05555] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb566cbb0da]
[runnervmeorf1:05555] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb566ca5a55]
[runnervmeorf1:05555] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb566ca5a6f]
[runnervmeorf1:05555] [ 8] plumed_master(+0x146dd)[0x5575bfaec6dd]
[runnervmeorf1:05555] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb56682a1ca]
[runnervmeorf1:05555] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb56682a28b]
[runnervmeorf1:05555] [11] plumed_master(+0x15365)[0x5575bfaed365]
[runnervmeorf1:05555] *** End of error message ***
</pre>
{% endraw %}
