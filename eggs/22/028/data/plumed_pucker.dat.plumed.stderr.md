**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[fv-az1442-469:07316] *** Process received signal ***
[fv-az1442-469:07316] Signal: Aborted (6)
[fv-az1442-469:07316] Signal code:  (-6)
[fv-az1442-469:07316] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0ebd442520]
[fv-az1442-469:07316] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0ebd4969fc]
[fv-az1442-469:07316] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0ebd442476]
[fv-az1442-469:07316] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0ebd4287f3]
[fv-az1442-469:07316] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0ebd8a2b9e]
[fv-az1442-469:07316] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0ebd8ae20c]
[fv-az1442-469:07316] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0ebd8ae277]
[fv-az1442-469:07316] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0ebd8ae52b]
[fv-az1442-469:07316] [ 8] plumed(+0x14254)[0x55f7c0dd9254]
[fv-az1442-469:07316] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0ebd429d90]
[fv-az1442-469:07316] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0ebd429e40]
[fv-az1442-469:07316] [11] plumed(+0x14eb5)[0x55f7c0dd9eb5]
[fv-az1442-469:07316] *** End of error message ***
</pre>
{% endraw %}
