# OpenStoreCustomAction
Custom Action Plugin

Custom Action Plugins are designed to run a 1 time update of data, in the DB, without the need of a UI.
Usually a selection of data records from the DB will be done and then an action and update performed.

The resulting dll from this project can be copied into the /bin folder of the DNN/NBS installation and then ran using the AdminPanel>Admin>Tools option.
e.g. for this provider name. (Alter as required)
assembly: OpenStore.BaseCustomAction
namespace.class: Nevoweb.OpenStore.CustomAction

NOTE: change the namespace of "Nevoweb." and the assembly name.
		