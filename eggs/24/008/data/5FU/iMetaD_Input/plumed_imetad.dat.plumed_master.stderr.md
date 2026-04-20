**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  5FU/iMetaD_Input/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[runnervmeorf1:05388] *** Process received signal ***
[runnervmeorf1:05388] Signal: Aborted (6)
[runnervmeorf1:05388] Signal code:  (-6)
[runnervmeorf1:05388] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f313d645330]
[runnervmeorf1:05388] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f313d69eb2c]
[runnervmeorf1:05388] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f313d64527e]
[runnervmeorf1:05388] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f313d6288ff]
[runnervmeorf1:05388] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f313daa5ff5]
[runnervmeorf1:05388] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f313dabb0da]
[runnervmeorf1:05388] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f313daa5a55]
[runnervmeorf1:05388] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f313daa5a6f]
[runnervmeorf1:05388] [ 8] plumed_master(+0x146dd)[0x5559b19006dd]
[runnervmeorf1:05388] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f313d62a1ca]
[runnervmeorf1:05388] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f313d62a28b]
[runnervmeorf1:05388] [11] plumed_master(+0x15365)[0x5559b1901365]
[runnervmeorf1:05388] *** End of error message ***
</pre>
{% endraw %}
