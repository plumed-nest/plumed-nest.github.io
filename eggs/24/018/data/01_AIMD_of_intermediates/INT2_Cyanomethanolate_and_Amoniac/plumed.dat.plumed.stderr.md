**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:07520] *** Process received signal ***
[runnervm0kj6c:07520] Signal: Aborted (6)
[runnervm0kj6c:07520] Signal code:  (-6)
[runnervm0kj6c:07520] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3744a45330]
[runnervm0kj6c:07520] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3744a9eb2c]
[runnervm0kj6c:07520] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3744a4527e]
[runnervm0kj6c:07520] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3744a288ff]
[runnervm0kj6c:07520] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3744ea5ff5]
[runnervm0kj6c:07520] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3744ebb0da]
[runnervm0kj6c:07520] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3744ea5a55]
[runnervm0kj6c:07520] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3744ea5a6f]
[runnervm0kj6c:07520] [ 8] plumed(+0x146dd)[0x55bb8ded86dd]
[runnervm0kj6c:07520] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3744a2a1ca]
[runnervm0kj6c:07520] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3744a2a28b]
[runnervm0kj6c:07520] [11] plumed(+0x15365)[0x55bb8ded9365]
[runnervm0kj6c:07520] *** End of error message ***
</pre>
{% endraw %}
