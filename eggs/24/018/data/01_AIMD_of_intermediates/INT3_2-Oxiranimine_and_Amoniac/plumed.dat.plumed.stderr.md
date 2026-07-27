**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmvrwv9:06180] *** Process received signal ***
[runnervmvrwv9:06180] Signal: Aborted (6)
[runnervmvrwv9:06180] Signal code:  (-6)
[runnervmvrwv9:06180] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9907845330]
[runnervmvrwv9:06180] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f990789eb2c]
[runnervmvrwv9:06180] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f990784527e]
[runnervmvrwv9:06180] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f99078288ff]
[runnervmvrwv9:06180] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9907ca5ff5]
[runnervmvrwv9:06180] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9907cbb0da]
[runnervmvrwv9:06180] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9907ca5a55]
[runnervmvrwv9:06180] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9907ca5a6f]
[runnervmvrwv9:06180] [ 8] plumed(+0x146dd)[0x56202c8ed6dd]
[runnervmvrwv9:06180] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f990782a1ca]
[runnervmvrwv9:06180] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f990782a28b]
[runnervmvrwv9:06180] [11] plumed(+0x15365)[0x56202c8ee365]
[runnervmvrwv9:06180] *** End of error message ***
</pre>
{% endraw %}
