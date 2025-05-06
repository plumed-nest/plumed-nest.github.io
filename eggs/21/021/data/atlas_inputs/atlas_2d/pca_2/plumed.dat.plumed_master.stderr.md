**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1050-229:65338] *** Process received signal ***
[fv-az1050-229:65338] Signal: Aborted (6)
[fv-az1050-229:65338] Signal code:  (-6)
[fv-az1050-229:65338] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faee7045330]
[fv-az1050-229:65338] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faee709eb2c]
[fv-az1050-229:65338] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faee704527e]
[fv-az1050-229:65338] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faee70288ff]
[fv-az1050-229:65338] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faee74a5ff5]
[fv-az1050-229:65338] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faee74bb0da]
[fv-az1050-229:65338] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faee74a5a55]
[fv-az1050-229:65338] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faee74a5a6f]
[fv-az1050-229:65338] [ 8] plumed_master(+0x146dd)[0x558cf670f6dd]
[fv-az1050-229:65338] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faee702a1ca]
[fv-az1050-229:65338] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faee702a28b]
[fv-az1050-229:65338] [11] plumed_master(+0x15365)[0x558cf6710365]
[fv-az1050-229:65338] *** End of error message ***
</pre>
{% endraw %}
