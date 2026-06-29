**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_alanine_dp.dat   
Download: [zipped raw stdout](plumed_alanine_dp.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_alanine_dp.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file reference.pdb
[runnervmmklqx:07087] *** Process received signal ***
[runnervmmklqx:07087] Signal: Aborted (6)
[runnervmmklqx:07087] Signal code:  (-6)
[runnervmmklqx:07087] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f67e3845330]
[runnervmmklqx:07087] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f67e389eb2c]
[runnervmmklqx:07087] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f67e384527e]
[runnervmmklqx:07087] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67e38288ff]
[runnervmmklqx:07087] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67e3ca5ff5]
[runnervmmklqx:07087] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67e3cbb0da]
[runnervmmklqx:07087] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67e3ca5a55]
[runnervmmklqx:07087] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67e3ca5a6f]
[runnervmmklqx:07087] [ 8] plumed_master(+0x146dd)[0x559aa1c116dd]
[runnervmmklqx:07087] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f67e382a1ca]
[runnervmmklqx:07087] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f67e382a28b]
[runnervmmklqx:07087] [11] plumed_master(+0x15365)[0x559aa1c12365]
[runnervmmklqx:07087] *** End of error message ***
</pre>
{% endraw %}
