### Js code

function toggleActiveclass(element){
	require([
		'jquery',
	], function(jQuery){
		(function($) {
			$(element).toggleClass('active');
		})(jQuery);
	});
}
