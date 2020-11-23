<template>
    <div class="container">
        <p class="mb-5">.tile.is-ancestor</p>
        <div class="tile is-ancestor box">
            .tile.is-ancestor обернет все остальные плитки
        </div>
        <hr>
        <p class="mb">.tile.is-ancestor</p>
        <p class="ml-2">.tile.is-parent.is-4</p>
        <p class="ml-4">.tile.is-child</p>
        <p class="ml-2">.tile.is-parent</p>
        <p class="ml-4 mb-5">.tile.is-child</p>
        <div class="tile is-ancestor">
            <div class="tile tile-1 is-parent is-4">
                <div class="tile is-child box">
                    Добавьте элементы плитки, которые будут располагаться по горизонтали :
                </div>
            </div>
            <div class="tile tile-1 is-parent box">
                <div class="tile is-child box">
                    Добавьте элементы плитки, которые будут располагаться по горизонтали :
                </div>
            </div>
        </div>
        <hr>
        <p class="mb">.tile.is-ancestor</p>
        <p class="ml-2">.tile.is-4.is-vertical.is-parent</p>
        <p class="ml-5">.tile.is-child</p>
        <p class="ml-5">.tile.is-child</p>
        <p class="ml-2">.tile.is-parent</p>
        <p class="ml-5">.tile.is-child</p>
        <p class="ml-5 mb-5">.tile.is-child</p>
        <div class="tile is-ancestor">
            <div class="tile is-4 tile-1 is-vertical is-parent">
                <div class="tile is-child box">
                    Если вы хотите укладывать плитки вертикально , добавьте is-verticalк родительской плитке:

                </div>
                <div class="tile is-child box">
                    Если вы хотите укладывать плитки вертикально , добавьте is-verticalк родительской плитке:
                </div>
            </div>
            <div class="tile is-parent tile-1">
                <div class="tile is-child box">
                    Если вы хотите укладывать плитки вертикально , добавьте is-vertical к родительской плитке:
                </div>
            </div>
        </div>
        <hr>
        <p>1|.tile.is-ancestor</p>
        <p class="ml-2">2|.tile.is-vertical</p>
        <p class="ml-3">3|.tile.is-parent</p>
        <p class="ml-4">4|.tile.is-parent.is-vertical</p>
        <p class="ml-5">5|.tile.is-parent</p>
        <p class="ml-6">|.tile.is-child</p>
        <p class="ml-5">5|.tile.is-parent</p>
        <p class="ml-6">|.tile.is-child</p>
        <p class="ml-4">4|.tile.is-parent</p>
        <p class="ml-6">|.tile.is-child</p>
        <p class="ml-3">3|.tile.is-parent</p>
        <p class="ml-4">|.tile.is-child // </p>
        <p class="ml-2">2|.tile.is-parent</p>
        <p class="ml-4 mb-5">|.tile.is-child</p>
       
        
        <div class="tile is-ancestor">1
            <div class="tile is-vertical is-parent">
               2
                <div class="tile is-parent">
                   3
                    <div class="tile is-vertical is-parent">
                       4
                        <div class="tile is-parent">
                            <div class="tile tile-child box tile-1">
                                5
                            </div>
                        </div>
                        <div class="tile is-parent">
                            <div class="tile tile-child box tile-1">
                                5
                            </div>
                        </div>
                    </div>
                    <div class="tile is-parent">
                       
                        <div class="tile is-child box tile-1">
                           4
                        </div>
                    </div>
                </div>
                
                <div class="tile is-parent">
                    <div class="tile is-child tile-1 box">
                        3
                    </div>
                </div>
            </div>
            <div class="tile is-parent">
                <div class="tile is-child box tile-1">
                    2
                </div>
            </div>
        </div>


    </div>

</template>
<style>
    hr {
        background-color: #bf8f0c;
        height: 3px;
    }

    .tile {
        background-color: #aaa5a5;
    }

    .tile-1 {
        background-color: #cc4d4d;
    }

    .tile-5 {
        background-color: #85b42c;
    }

</style>
<!--   <p>.tile.is-ancestor</p>
  <p class="ml-2">.tile</p>
  <p class="ml-2">.tile</p>
  <p class="ml-2">.tile</p>
  <p class="ml-2 mb-5">.tile</p>
   <div class="tile is-ancestor">
     <div class="tile is-parent tile-1">
     <div class="box">horizontal</div></div>
     <div class="tile is-parent tile-2"><div class="box">horizontal</div></div>
     <div class="tile is-parent tile-3"><div class="box">horizontal</div></div>
     <div class="tile is-parent tile-4"><div class="box">horizontal</div></div>
   </div>
   <hr>
   <p>.tile.is-ancestor</p>
  <p class="ml-2">.tile</p>
  <p class="ml-2">.tile</p>
  <p class="ml-2">.tile</p>
  <p class="ml-2 mb-5">.tile</p>
   <div class="tile is-ancestor">
     <div class="tile is-parent tile-1 is-vertical">
     <div class="tile is-child">1</div>
     <div class="tile is-child">2</div>
     <div class="tile is-child">3</div>
     </div>
     <div class="tile is-parent tile-2"><div class="box">horizontal</div></div>
     <div class="tile is-parent tile-3"><div class="box">horizontal</div></div>
     <div class="tile is-parent tile-4"><div class="box">horizontal</div></div>
   </div>

<hr>
   <div class="tile is-ancestor">
     <div class="tile tile-1 is-vertical is-parent">
       <div class="tile tile-3 is-child">1</div>
     </div>
     <div class="tile tile-2 is-parent">
        <div class="tile tile-4 is-child">1</div>
        <div class="tile tile-4 is-child">1</div>
        <div class="tile tile-4 is-child">1</div>
     </div>
   </div>
<hr>
<div class="tile is-ancestor">
  <div class="tile is-vertical  is-parent">
    <div class="tile tile-1 is-child box">
      <p class="title">One</p>
    </div>
    <div class="tile is-child box">
      <p class="title">Two</p>
    </div>
  </div>
  <div class="tile is-parent">
    <div class="tile  tile-2 is-child box">
      <p class="title">Three</p>
    </div>
  </div>
</div>-->
