**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:547) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled @6.bias in in grid input
[fv-az1442-469:10094] *** Process received signal ***
[fv-az1442-469:10094] Signal: Aborted (6)
[fv-az1442-469:10094] Signal code:  (-6)
[fv-az1442-469:10094] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc605442520]
[fv-az1442-469:10094] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc6054969fc]
[fv-az1442-469:10094] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc605442476]
[fv-az1442-469:10094] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc6054287f3]
[fv-az1442-469:10094] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc6058a2b9e]
[fv-az1442-469:10094] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc6058ae20c]
[fv-az1442-469:10094] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc6058ae277]
[fv-az1442-469:10094] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc6058ae52b]
[fv-az1442-469:10094] [ 8] plumed(+0x14254)[0x55dd90ccb254]
[fv-az1442-469:10094] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc605429d90]
[fv-az1442-469:10094] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc605429e40]
[fv-az1442-469:10094] [11] plumed(+0x14eb5)[0x55dd90ccbeb5]
[fv-az1442-469:10094] *** End of error message ***
</pre>
{% endraw %}
