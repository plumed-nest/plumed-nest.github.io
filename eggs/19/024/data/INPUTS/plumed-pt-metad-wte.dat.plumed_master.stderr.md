**Project ID:** [plumID:19.024]({{ '/' | absolute_url }}eggs/19/024/)  
Stderr for source:  INPUTS/plumed-pt-metad-wte.dat   
Download: [zipped raw stdout](plumed-pt-metad-wte.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-pt-metad-wte.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Grid.cpp:655) static std::unique_ptr<PLMD::GridBase> PLMD::GridBase::create(const std::string&, const std::vector<PLMD::Value*>&, PLMD::IFile&, bool, bool, bool)
+++ assertion failed: ifile.FieldExist( funcl )
no column labelled @6.bias in in grid input
[fv-az1344-582:68119] *** Process received signal ***
[fv-az1344-582:68119] Signal: Aborted (6)
[fv-az1344-582:68119] Signal code:  (-6)
[fv-az1344-582:68119] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fceb7e45330]
[fv-az1344-582:68119] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fceb7e9eb2c]
[fv-az1344-582:68119] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fceb7e4527e]
[fv-az1344-582:68119] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fceb7e288ff]
[fv-az1344-582:68119] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fceb82a5ff5]
[fv-az1344-582:68119] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fceb82bb0da]
[fv-az1344-582:68119] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fceb82a5a55]
[fv-az1344-582:68119] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fceb82a5a6f]
[fv-az1344-582:68119] [ 8] plumed_master(+0x146dd)[0x5582d9a886dd]
[fv-az1344-582:68119] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fceb7e2a1ca]
[fv-az1344-582:68119] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fceb7e2a28b]
[fv-az1344-582:68119] [11] plumed_master(+0x15365)[0x5582d9a89365]
[fv-az1344-582:68119] *** End of error message ***
</pre>
{% endraw %}
