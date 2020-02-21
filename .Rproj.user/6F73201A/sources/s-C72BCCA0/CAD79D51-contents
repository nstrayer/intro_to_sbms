// Macros for Xaringan

remark.macros.centerPic = function (percentage, bordered) {
  const url = this;
  return `<div style="text-align:center; ${bordered ? "border: 1px solid black;": ""}"> <img src='${url}' width = ${percentage}%/> </div>`;
};

remark.macros.borderedCenterPic = function (percentage) {
  const url = this;
  return `<div style="text-align:center; "> <img style = "border: 1px solid black; box-shadow: 4px 4px 4px 0px rgba(0,0,0,0.75);" src='${url}' width = ${percentage}%/> </div>`;
};


remark.macros.colorText = function(color) {
  const text = this;
  return `<span style="color:${color}">${text}</span>`;
};

remark.macros.space = function(percentage) {
  return `<div style="height: ${percentage}%"></div>`;
};

remark.macros.indent = function(pixels){
  return `<span style="margin-right: ${pixels | 40}px"></span>`;
};


remark.macros.small = function(shrink_amnt){
  const text = this;
  return `<span style="font-size: ${shrink_amnt}em;"> ${text} </span>`;
};

