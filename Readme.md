# SCSS Masterclass

(S)CSS Layout Masterclass: Flexbox & Grid

## Flexbox:

- [x] flex-direction
- [x] order
- [x] justify-content
- [x] align-items
- [x] align-self
- [x] flex-wrap
- [x] align-content
- [x] flex-grow
- [x] flex-shrink
- [x] flex-basis

## Grid:


● grid-column: (start) / (end);
● grid-row: (start) / (end);
● -1, -2, -3, ··· ▷ 끝에서부터 line 세기
● (start) / span (cell 수) ▷ 시작점과 끝점을 적는걸 대신한다.

grid naming line을 만들수있는데,
column, row 둘다 적용이 가능함
ex) grid-columns: [fuckyou-start] 100 [column-start]- 100
이런식으로 계속 적어주면되고
또한
grid 내장 함수인 repeat에서도 사용이간으함. repeat(4, [sexy-line] 100px) == grid-row = 100px [sexy-line] 100px [sexy-line] 와 같음.
다만 repeat로 사용하면서 네이밍을 넣을경우 처읆이 존재하지않음. sexy-line 1 / sexy-line 3 은 가능하지만 sexy-line 2 / sexy-line은 불가능함 처음이 없기때문에 2번째부터 시작함.

- [x] grid-template-columns
- [x] grid-template-rows
- [x] grid-column-gap
- [x] grid-row-gap
- [x] grid-gap
- [x] grid-template-areas
- [ ] grid-template
- [ ] justify-items
- [ ] align-items
- [ ] justify-content
- [ ] align-content
- [ ] grid-auto-columns
- [ ] grid-auto-rows
- [ ] grid-auto-flow
- [x] grid-column-start
- [x] grid-column-end
- [x] grid-row-start
- [x] grid-row-end
- [x] grid-column
- [x] grid-row
- [ ] justify-self
- [ ] align-self

### Keywords & Functions:

- [ ] repeat
- [ ] min-content
- [ ] max-content
- [ ] minmax
- [ ] auto-fit
- [ ] auto-fill

## SCSS:

- [ ] Variables
- [ ] Nesting
- [ ] Partials
- [ ] Mixins
- [ ] Extend
- [ ] Responsive