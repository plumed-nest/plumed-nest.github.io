**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2pr_Hydroxydeacetonitrile_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1050-229:62211] *** Process received signal ***
[fv-az1050-229:62211] Signal: Aborted (6)
[fv-az1050-229:62211] Signal code:  (-6)
[fv-az1050-229:62211] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9e80c45330]
[fv-az1050-229:62211] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9e80c9eb2c]
[fv-az1050-229:62211] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9e80c4527e]
[fv-az1050-229:62211] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9e80c288ff]
[fv-az1050-229:62211] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9e810a5ff5]
[fv-az1050-229:62211] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9e810bb0da]
[fv-az1050-229:62211] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9e810a5a55]
[fv-az1050-229:62211] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9e810a5a6f]
[fv-az1050-229:62211] [ 8] plumed(+0x146dd)[0x55dc0e91e6dd]
[fv-az1050-229:62211] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9e80c2a1ca]
[fv-az1050-229:62211] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9e80c2a28b]
[fv-az1050-229:62211] [11] plumed(+0x15365)[0x55dc0e91f365]
[fv-az1050-229:62211] *** End of error message ***
</pre>
{% endraw %}
