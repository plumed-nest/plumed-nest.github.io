**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2pr_Hydroxydeacetonitrile_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:07671] *** Process received signal ***
[runnervmw9dnm:07671] Signal: Aborted (6)
[runnervmw9dnm:07671] Signal code:  (-6)
[runnervmw9dnm:07671] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5614845330]
[runnervmw9dnm:07671] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f561489eb2c]
[runnervmw9dnm:07671] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f561484527e]
[runnervmw9dnm:07671] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f56148288ff]
[runnervmw9dnm:07671] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5614ca5ff5]
[runnervmw9dnm:07671] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5614cbb0da]
[runnervmw9dnm:07671] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5614ca5a55]
[runnervmw9dnm:07671] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5614ca5a6f]
[runnervmw9dnm:07671] [ 8] plumed_master(+0x146dd)[0x55a7e7fec6dd]
[runnervmw9dnm:07671] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f561482a1ca]
[runnervmw9dnm:07671] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f561482a28b]
[runnervmw9dnm:07671] [11] plumed_master(+0x15365)[0x55a7e7fed365]
[runnervmw9dnm:07671] *** End of error message ***
</pre>
{% endraw %}
