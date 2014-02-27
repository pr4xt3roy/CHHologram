CHHologram
==========

A collection of procs commands and binds to create the hologram like effect in Minecraft.



=================== [ FUNCTIONS ] ===================

#####\_location_standardize( @location )

Given a partial location array it will fill in missing parameters so a consistant location array is used.



#####\_spawn_hologram( @lines, @location = null, @alignment = 0.3 )

This creates a hologram @location with the following @lines. If @alignment is specified the spacing between the lines is changed.



#####\_remove_hologram( @id )

Removes a given hologram with @id if it exists. Returns true if successful or false if not.



#####\_holograms\_in_radius( @location, @distance )

Returns a array of ids for holograms within a 3D @distance.



#####\_all_holograms()

Returns a array of all holograms, a blank array is returned if there are none.



#####\_hologram_exists( @id )

Returns true if the hologram with @id exists, otherwise false.



#####\_get\_hologram_loc( @id )

Returns the location array of a hologram with @id if it exists, nothing if otherwise.



#####\_set\_hologram_loc( @id, @location = null )

Recreates @id hologram at @location and returns true if successful, false is returned otherwise.



#####\_get\_hologram_text( @id )

Returns @id hologram's text. If the hologram doesnt exist false is returned.



#####\_set\_hologram_text( @id, @textArray )

Sets @id hologram's text to @textArray, returns true if successful, false if otherwise.



