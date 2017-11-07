Append output and generated errors to an existing files

* `[student@desktopX ~] find /etc -name passwd > /tmp/output 2> /tmp/errors`
* `[student@desktopX ~] find /etc -name passwd 2> /tmp/errors`
* `[student@desktopX ~] find /etc -name passwd > /tmp/output 2> /dev/null`
+ `[student@desktopX ~] find /etc -name passwd >> /tmp/save-both 2>&1`
* `[student@desktopX ~] find /etc -name passwd &> /tmp/save-both`
