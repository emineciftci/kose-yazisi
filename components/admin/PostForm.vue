<template>
  <div class="container-fluid mt-5 d-flex flex-wrap justify-content-center align-items-center">
    <form style="width: 500px">
        <fieldset>
            <legend>Yeni Köse Yazısı</legend>
            <div class="form-group">
                <label>Yazar Adı</label>
                <input type="text" class="form-control" placeholder="Yazarın adını giriniz..">
            </div>
            <div class="form-group">
                <label>Baslık</label>
                <input type="text" class="form-control" placeholder="Yazının baslıgını giriniz..">
            </div>
            <div class="form-group">
                <label>Alt Baslık</label>
                <input type="text" class="form-control" placeholder="Yazının alt baslıgını giriniz..">
            </div>
            <div class="form-group">
                <label for="exampleTextarea">Köse Yazısı</label>
                <textarea class="form-control" rows="5"></textarea>
            </div>
            <button class="btn btn-danger">İptal</button>
            <button type="submit" class="btn btn-primary">Kaydet</button>
        </fieldset>
    </form>
</div>
</template>
