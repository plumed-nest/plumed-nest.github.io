**Project ID:** [plumID:25.021]({{ '/' | absolute_url }}eggs/25/021/)  
Stderr for source:  S5-G4/anti_bulk_fp/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action FIT_TO_TEMPLATE with label @8 : missing input file conf_template.pdb
[runnervmeorf1:05391] *** Process received signal ***
[runnervmeorf1:05391] Signal: Aborted (6)
[runnervmeorf1:05391] Signal code:  (-6)
[runnervmeorf1:05391] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faa88245330]
[runnervmeorf1:05391] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faa8829eb2c]
[runnervmeorf1:05391] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faa8824527e]
[runnervmeorf1:05391] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faa882288ff]
[runnervmeorf1:05391] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faa886a5ff5]
[runnervmeorf1:05391] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faa886bb0da]
[runnervmeorf1:05391] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faa886a5a55]
[runnervmeorf1:05391] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faa886a5a6f]
[runnervmeorf1:05391] [ 8] plumed(+0x146dd)[0x562199f4c6dd]
[runnervmeorf1:05391] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faa8822a1ca]
[runnervmeorf1:05391] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faa8822a28b]
[runnervmeorf1:05391] [11] plumed(+0x15365)[0x562199f4d365]
[runnervmeorf1:05391] *** End of error message ***
</pre>
{% endraw %}
