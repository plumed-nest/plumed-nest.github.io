**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action MATHEVAL with label ns : action nsa has no component named nsa (hint! the components in this actions are: )
[fv-az530-623:10453] *** Process received signal ***
[fv-az530-623:10453] Signal: Aborted (6)
[fv-az530-623:10453] Signal code:  (-6)
[fv-az530-623:10453] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fabc9c42520]
[fv-az530-623:10453] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fabc9c969fc]
[fv-az530-623:10453] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fabc9c42476]
[fv-az530-623:10453] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fabc9c287f3]
[fv-az530-623:10453] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fabca0a2b9e]
[fv-az530-623:10453] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fabca0ae20c]
[fv-az530-623:10453] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fabca0ae277]
[fv-az530-623:10453] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fabca0ae52b]
[fv-az530-623:10453] [ 8] plumed(+0x12f48)[0x55a16561ef48]
[fv-az530-623:10453] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fabc9c29d90]
[fv-az530-623:10453] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fabc9c29e40]
[fv-az530-623:10453] [11] plumed(+0x131e5)[0x55a16561f1e5]
[fv-az530-623:10453] *** End of error message ***
</pre>
{% endraw %}
