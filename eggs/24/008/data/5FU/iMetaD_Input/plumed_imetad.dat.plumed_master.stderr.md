**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  5FU/iMetaD_Input/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[runnervmvrwv9:05413] *** Process received signal ***
[runnervmvrwv9:05413] Signal: Aborted (6)
[runnervmvrwv9:05413] Signal code:  (-6)
[runnervmvrwv9:05413] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcae0845330]
[runnervmvrwv9:05413] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcae089eb2c]
[runnervmvrwv9:05413] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcae084527e]
[runnervmvrwv9:05413] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcae08288ff]
[runnervmvrwv9:05413] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcae0ca5ff5]
[runnervmvrwv9:05413] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcae0cbb0da]
[runnervmvrwv9:05413] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcae0ca5a55]
[runnervmvrwv9:05413] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcae0ca5a6f]
[runnervmvrwv9:05413] [ 8] plumed_master(+0x146dd)[0x5561a1f156dd]
[runnervmvrwv9:05413] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcae082a1ca]
[runnervmvrwv9:05413] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcae082a28b]
[runnervmvrwv9:05413] [11] plumed_master(+0x15365)[0x5561a1f16365]
[runnervmvrwv9:05413] *** End of error message ***
</pre>
{% endraw %}
