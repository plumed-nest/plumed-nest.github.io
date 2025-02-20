**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[fv-az1372-996:07944] *** Process received signal ***
[fv-az1372-996:07944] Signal: Aborted (6)
[fv-az1372-996:07944] Signal code:  (-6)
[fv-az1372-996:07944] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa27b845330]
[fv-az1372-996:07944] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa27b89eb2c]
[fv-az1372-996:07944] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa27b84527e]
[fv-az1372-996:07944] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa27b8288ff]
[fv-az1372-996:07944] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa27bca5ff5]
[fv-az1372-996:07944] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa27bcbb0da]
[fv-az1372-996:07944] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa27bca5a55]
[fv-az1372-996:07944] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa27bca5a6f]
[fv-az1372-996:07944] [ 8] plumed(+0x146dd)[0x557e741a26dd]
[fv-az1372-996:07944] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa27b82a1ca]
[fv-az1372-996:07944] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa27b82a28b]
[fv-az1372-996:07944] [11] plumed(+0x15365)[0x557e741a3365]
[fv-az1372-996:07944] *** End of error message ***
</pre>
{% endraw %}
