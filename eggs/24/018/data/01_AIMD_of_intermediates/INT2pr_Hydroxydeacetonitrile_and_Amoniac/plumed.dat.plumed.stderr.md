**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2pr_Hydroxydeacetonitrile_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm0kj6c:07676] *** Process received signal ***
[runnervm0kj6c:07676] Signal: Aborted (6)
[runnervm0kj6c:07676] Signal code:  (-6)
[runnervm0kj6c:07676] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb2d1645330]
[runnervm0kj6c:07676] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb2d169eb2c]
[runnervm0kj6c:07676] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb2d164527e]
[runnervm0kj6c:07676] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb2d16288ff]
[runnervm0kj6c:07676] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb2d1aa5ff5]
[runnervm0kj6c:07676] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb2d1abb0da]
[runnervm0kj6c:07676] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb2d1aa5a55]
[runnervm0kj6c:07676] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb2d1aa5a6f]
[runnervm0kj6c:07676] [ 8] plumed(+0x146dd)[0x562fdd2866dd]
[runnervm0kj6c:07676] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb2d162a1ca]
[runnervm0kj6c:07676] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb2d162a28b]
[runnervm0kj6c:07676] [11] plumed(+0x15365)[0x562fdd287365]
[runnervm0kj6c:07676] *** End of error message ***
</pre>
{% endraw %}
