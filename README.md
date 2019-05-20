# eBookManager

The eBook Manager application is a basic Windows application that manages your eBook collection by way of Virtual Storage Spaces. 
Your eBooks are still physically stored in the same location on your hard drive, but they are logically grouped and stored in one of several virtual Storage Spaces as created by yourself.
This project is created to showcase some of the new features in C# 7.0. 
You will find a list below that shows you where to see the examples of each new feature as implemented in the eBookManager application.

## New features in C# 7.0

### Tuples
Example in GetFileProperties() in DocumentEngine.cs

### Pattern matching
Example in PopulateStorageSpacesList() in ImportBooks.cs

### Out variables
Example in ToInt() Extension Method in ExtensionMethods.cs
Example in ToDecimal() Extension Method in ExtensionMethods.cs
Example in ToDouble() Extension Method in ExtensionMethods.cs
Example in btnSaveNewStorageSpace_Click in Extension Method Call StorageSpaceExists(newName, out int nextID) in ImportBooks.cs

### Deconstruction and Local functions
Example in PopulateStorageSpacesList() in ImportBooks.cs

### Improvements to literals
### Ref returns and locals
### Generalized async return types
### Expression bodies for accessors, constructors and finalizers
Example in ImportBook.cs property AllowedExtensions

### throw expressions
Example in btnSaveNewStorageSpace_Click in ImportBooks.cs
Example in btnAddeBookToStorageSpace_Click in ImportBooks.cs