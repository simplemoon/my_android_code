if can't create a new class, do next:
In your, IntelliJ IDE go to Help => Edit Custom VM Options and Add to your idea.vmoptions or idea64.vmoptions the following line:

-Djdk.util.zip.ensureTrailingSlash=false



