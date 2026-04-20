**Project ID:** [plumID:25.021]({{ '/' | absolute_url }}eggs/25/021/)  
Stderr for source:  S5-G1/anti_bulk_fp/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action FIT_TO_TEMPLATE with label @8 : missing input file conf_template.pdb
[runnervmeorf1:04927] *** Process received signal ***
[runnervmeorf1:04927] Signal: Aborted (6)
[runnervmeorf1:04927] Signal code:  (-6)
[runnervmeorf1:04927] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcfdd845330]
[runnervmeorf1:04927] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcfdd89eb2c]
[runnervmeorf1:04927] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcfdd84527e]
[runnervmeorf1:04927] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcfdd8288ff]
[runnervmeorf1:04927] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcfddca5ff5]
[runnervmeorf1:04927] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcfddcbb0da]
[runnervmeorf1:04927] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcfddca5a55]
[runnervmeorf1:04927] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcfddca5a6f]
[runnervmeorf1:04927] [ 8] plumed(+0x146dd)[0x5565c83e96dd]
[runnervmeorf1:04927] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcfdd82a1ca]
[runnervmeorf1:04927] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcfdd82a28b]
[runnervmeorf1:04927] [11] plumed(+0x15365)[0x5565c83ea365]
[runnervmeorf1:04927] *** End of error message ***
</pre>
{% endraw %}
