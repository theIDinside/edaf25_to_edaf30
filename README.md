# edaf25_to_edaf30
Converting the edaf25 workspace (Java) to edaf30 (C++)

- Different GUI toolkits require different considerations. Questions like, are they not thread-safe, partly or fully threadsafe? The school project itself, is implemented in Java with the Swing toolkit, which as far as I remember is not thread-safe (which is the point).

For c++, there's a multitude of GUI Toolkits, but there are two major contenders really:
- wxWidgets
- GTKmm (c++ binding for GTK+3-0)
