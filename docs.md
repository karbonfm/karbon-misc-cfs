## RemoveDuplicates ( Text)```/**
 * 
 * remeove duplicates from a List
 *
 * @param {string} Text the list to de-dup
 *
 * @returns {string} the new list
 *
 * @module karbon-misc-cfs
 * @see https://github.com/karbonfm/karbon-misc-cfs
 * 
 * @history  2017-11-17, todd@geistinteractive.com
 *
 */```## ListIncludes ( theList;theItem)```/**
 * 
 * Test if the list contains the item
 *
 * @param {string} theList
 * @param {string} theItem
 *
 * @returns {boolean}
 *
 * @module karbon-misc-cfs
 * @see https://github.com/karbonfm/karbon-misc-cfs
 * 
 * @history  2017-11-17, todd@geistinteractive.com
 *
 */```## IsValidEmailFormat ( text)```/**
 * 
 * Test for valid email
 *
 * Since new top-level domains are constantly added, this function 
  * assumes the top-level domain is legitimate and validates only the 
  * email format.
 *
 * @param {string} text
 *
 * @returns {boolean}
 *
 * @module karbon-misc-cfs
 * @see https://github.com/karbonfm/karbon-misc-cfs
 * 
 * @history  2008-11-17, mike@allieddataservice.com, created
 * @history  2010-12-05, mike@allieddataservice.com, created
 *
 */```## FilterValuesByExpression ( theList;expression)```/**
 * 
 * Filter a List with a FilerMaker Expression
 * 
 * if the expression is applied to each value in the List and 
 * if it evalutes to true then the Item is return.  Expressions 
 * can use "item" to refer to the List Item
 *
 * @param {string} theList
 * @param {string} expression
 *
 * @returns {string} the filtered list
 *
 * @module karbon-misc-cfs
 * @see https://github.com/karbonfm/karbon-misc-cfs
 * 
 * @history  2013-09-27, todd@geistinteractive.com
 *
 */```