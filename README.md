# Eat and Split

A simple basic app from jonas's react course on udemy


hard copy and flat array in javascript

const selectedIds = ["two", "four", "three", "one"];
const hardCopiedArr = nestedArray.map((el) => el.map((ele) => ({ ...ele }))); // copied nested array
const real = hardCopiedArr.flat();

const selectedObjs = selectedIds.map((el) => {
  const [selectedObj] = real.filter((ele) => ele.id === el);
  return { ...selectedObj };
});
