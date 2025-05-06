**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  FFH_scripts/plumed_FFH.dat   
Download: [zipped raw stdout](plumed_FFH.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FFH.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1050-229:65164] *** Process received signal ***
[fv-az1050-229:65164] Signal: Aborted (6)
[fv-az1050-229:65164] Signal code:  (-6)
[fv-az1050-229:65164] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2477445330]
[fv-az1050-229:65164] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f247749eb2c]
[fv-az1050-229:65164] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f247744527e]
[fv-az1050-229:65164] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24774288ff]
[fv-az1050-229:65164] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24778a5ff5]
[fv-az1050-229:65164] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24778bb0da]
[fv-az1050-229:65164] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24778a5a55]
[fv-az1050-229:65164] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24778a5a6f]
[fv-az1050-229:65164] [ 8] plumed(+0x146dd)[0x55af074056dd]
[fv-az1050-229:65164] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f247742a1ca]
[fv-az1050-229:65164] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f247742a28b]
[fv-az1050-229:65164] [11] plumed(+0x15365)[0x55af07406365]
[fv-az1050-229:65164] *** End of error message ***
</pre>
{% endraw %}
