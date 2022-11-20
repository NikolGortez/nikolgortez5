function click1()
{
	let price = document.getElementsByName("price");
    let count = document.getElementsByName("count");
    let result = document.getElementById("result");
	let toPrice = price[
        0
    ].value;
	let toCount = count[
        0
    ].value;
	let flag1 = toCount.match(/^\d+$/);
	let flag2 = toPrice.match(/^\d+$/);
	if(flag2 !== null && flag1 !== null)
	{
		result.innerHTML = parseInt(price[
            0
        ].value)*parseInt(count[
            0
        ].value);
    }
	else
	if(flag2 === null && flag1 !== null)
	{
		result.innerHTML = "Введите число в поле цена";
    }
	else
	if(flag1 === null && flag2 !== null)
	{
		result.innerHTML = "Введите число в поле количество";
    }
	else
	if(flag2 === null && flag1 === null)
	{
		result.innerHTML = "Введите число в оба поля";
    }
	return false;
}

function onClick()
{
	alert("Работа завершена");
}

window.addEventListener("DOMContentLoaded", function (event)
{
	console.log("DOM fully loaded and parsed");
	let b = document.getElementById("calculateResult");
	b.addEventListener("click", onClick);
});
