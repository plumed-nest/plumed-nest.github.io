**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:07087] *** Process received signal ***
[runnervmeorf1:07087] Signal: Aborted (6)
[runnervmeorf1:07087] Signal code:  (-6)
[runnervmeorf1:07087] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f18fe645330]
[runnervmeorf1:07087] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f18fe69eb2c]
[runnervmeorf1:07087] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f18fe64527e]
[runnervmeorf1:07087] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f18fe6288ff]
[runnervmeorf1:07087] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f18feaa5ff5]
[runnervmeorf1:07087] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f18feabb0da]
[runnervmeorf1:07087] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f18feaa5a55]
[runnervmeorf1:07087] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f18feaa5a6f]
[runnervmeorf1:07087] [ 8] plumed_master(+0x146dd)[0x55f45bd006dd]
[runnervmeorf1:07087] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f18fe62a1ca]
[runnervmeorf1:07087] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f18fe62a28b]
[runnervmeorf1:07087] [11] plumed_master(+0x15365)[0x55f45bd01365]
[runnervmeorf1:07087] *** End of error message ***
</pre>
{% endraw %}
