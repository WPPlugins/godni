=== GoDNI ===
Contributors: Alex Gonzales
Donate link: http://www.gopymes.pe
Tags: peruvian dni, person, trunk
Requires at least: 3.0.1
Tested up to: 3.0.1
Stable tag: 4.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin is a validator of peruvian DNI, however, this plugin need the 9 digits to validate correctly. NOTE: this one only validates the structure.

== Description ==

English
In the form register, admin panel or user profile; you can add the custom field DNI and the plugin will validate the structure using the 9 digits

Spanish
En el formulario de registro, el panel administrativo o el perfil de usuario; tu puedes agregar el campo personalizado DNI y el plugin validara la estructura usando los 9 digitos (tildes omitidas)

== Installation ==

1. Upload `godni.zip` to the `/wp-content/plugins/` directory
2. Unzip the plugin
3. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

English
--------

= How I can access the DNI of each user? =

Using the code <?php echo get_user_meta($user_id, 'dni', true); ?>

= Why do I have to put 9 digits, here everyone just remember the first 8 digits ? =

I'm sorry, but we need the 9th digit to validate the whole structure

= My 9th digit is a letter, there is problem in it? =

There isn't problem, the last digit can be number or letter

Spanish
--------

= Como puedo acceder al DNI de cada usuario? =

Usando el codigo <?php echo get_user_meta($user_id, 'dni', true); ?>

= Por que tengo que poner 9 digitos, aqui; todo el mundo solo recuerda los primeros 8 digitos? =

Lo siento, pero necesito el noveno digito para validar toda la estructura

= Mi noveno digito es una letra, no hay problema en ello? =

No hay problema, el ultimo digito puede ser numero o letra

(tildes omitidas)

== Screenshots ==

1. Form Register
2. Settings
3. Admin Panel
4. User Profile

== Changelog ==

= 1.0 =
* This plugin is new.
