**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[runnervmeorf1:05299] *** Process received signal ***
[runnervmeorf1:05299] Signal: Aborted (6)
[runnervmeorf1:05299] Signal code:  (-6)
[runnervmeorf1:05299] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc859045330]
[runnervmeorf1:05299] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc85909eb2c]
[runnervmeorf1:05299] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc85904527e]
[runnervmeorf1:05299] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc8590288ff]
[runnervmeorf1:05299] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc8594a5ff5]
[runnervmeorf1:05299] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc8594bb0da]
[runnervmeorf1:05299] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc8594a5a55]
[runnervmeorf1:05299] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc8594a5a6f]
[runnervmeorf1:05299] [ 8] plumed(+0x146dd)[0x557d77a226dd]
[runnervmeorf1:05299] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc85902a1ca]
[runnervmeorf1:05299] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc85902a28b]
[runnervmeorf1:05299] [11] plumed(+0x15365)[0x557d77a23365]
[runnervmeorf1:05299] *** End of error message ***
</pre>
{% endraw %}
