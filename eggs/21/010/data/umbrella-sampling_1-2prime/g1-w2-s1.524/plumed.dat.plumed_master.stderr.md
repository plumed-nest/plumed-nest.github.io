**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w2-s1.524/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1693-957:66143] *** Process received signal ***
[fv-az1693-957:66143] Signal: Aborted (6)
[fv-az1693-957:66143] Signal code:  (-6)
[fv-az1693-957:66143] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6a16045330]
[fv-az1693-957:66143] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6a1609eb2c]
[fv-az1693-957:66143] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6a1604527e]
[fv-az1693-957:66143] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6a160288ff]
[fv-az1693-957:66143] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6a164a5ff5]
[fv-az1693-957:66143] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6a164bb0da]
[fv-az1693-957:66143] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6a164a5a55]
[fv-az1693-957:66143] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6a164a5a6f]
[fv-az1693-957:66143] [ 8] plumed_master(+0x146dd)[0x55a8d92856dd]
[fv-az1693-957:66143] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6a1602a1ca]
[fv-az1693-957:66143] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6a1602a28b]
[fv-az1693-957:66143] [11] plumed_master(+0x15365)[0x55a8d9286365]
[fv-az1693-957:66143] *** End of error message ***
</pre>
{% endraw %}
